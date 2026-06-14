# HTTP Code With Cats — 과제보고서

> 2026 순천향대학교 웹프로그래밍 기말과제

## 1. 배포 URL

🔗 **https://wonchandev.github.io/HTTP_CAT/**

- GitHub 저장소: https://github.com/wonchandev/HTTP_CAT

## 2. 프로젝트 개요

**HTTP Code With Cats**는 어렵게 느껴지는 HTTP 응답 상태 코드를 귀여운 고양이 사진과 친근한 설명으로 쉽게 이해할 수 있도록 만든 웹사이트입니다.

[http.cat](https://http.cat) 의 고양이 이미지를 활용하여, 사용자가 고양이 사진을 클릭하면 해당 HTTP 상태 코드의 의미를 "고양이 말투"로 풀어 설명해 줍니다. 딱딱한 기술 문서 대신 누구나 재미있게 HTTP 코드를 학습할 수 있는 것이 핵심입니다.

## 3. 주요 기능

| 기능 | 설명 |
| --- | --- |
| HTTP 코드 갤러리 | 1xx ~ 5xx 까지 70여 개의 HTTP 상태 코드를 고양이 이미지 그리드로 한눈에 표시 |
| 상세 모달 팝업 | 고양이 사진을 클릭하면 해당 코드의 제목과 친근한 설명을 모달 창으로 제공 |
| 회원가입 / 로그인 | 사용자 인증을 위한 회원가입·로그인 폼 및 입력값 유효성 검사 |
| 반응형 디자인 | 모바일·태블릿·PC 등 다양한 화면 크기에 맞춰 자동 조정 |

## 4. 페이지 구성

- **index.html** — 메인 페이지 (HTTP 코드 고양이 갤러리 및 설명 모달)
- **join.html** — 회원가입 페이지 (입력값 유효성 검사 포함)
- **login.html** — 로그인 페이지

## 5. 사용 기술

- **HTML5** — 시맨틱 마크업 기반의 문서 구조
- **CSS3** — 그리드 레이아웃, 반응형 디자인, 모달 스타일링
- **JavaScript (Vanilla JS)** — 모달 제어, HTTP 코드 데이터 관리, 폼 유효성 검사
- **Pretendard 폰트** — JSDelivr CDN을 통한 웹폰트 적용
- **외부 리소스** — [http.cat](https://http.cat) 의 HTTP 상태 코드 고양이 이미지

## 6. 디렉터리 구조

```
HTTP_CAT/
├── index.html        # 메인 페이지
├── join.html         # 회원가입 페이지
├── login.html        # 로그인 페이지
├── css/
│   ├── style.css     # 메인 스타일
│   └── login.css     # 로그인/회원가입 스타일
├── js/
│   └── main.js       # HTTP 코드 데이터 및 모달 로직
└── README.md
```
