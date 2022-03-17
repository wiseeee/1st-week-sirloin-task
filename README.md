
<h1 align="middle">admin 페이지 제작</h1>

# 🔗 배포

https://pre-onboarding-course-team-6.github.io/1st-week-sirloin-task/

<br>

# 기술스택

<img alt="react" src="https://img.shields.io/badge/react-61DAFB?style=for-the-badge&logo=react&logoColor=black">

<img alt="styled-components" src="https://img.shields.io/badge/styledcomponents-DB7093?style=for-the-badge&logo=styled-components&logoColor=white"> <img alt="eslint" src="https://img.shields.io/badge/eslint-4B32C3?style=for-the-badge&logo=eslint&logoColor=white"> <img alt="prettier" src="https://img.shields.io/badge/prettier-F7B93E?style=for-the-badge&logo=prettier&logoColor=white">



<br>

# 🏹 기능 구현


![설로인](https://user-images.githubusercontent.com/82519641/158856473-63f9d81c-9ef2-4144-ab1f-f573d0b36dac.gif)

  - 카테고리 지정 및 삭제
  - checkbox on - 오른쪽으로 추가
  - checkbox off - 오른쪽에서 삭제

<br><br>
# 🏗 프로젝트 구조 설명

```
📦src
├──📂commons
│   ├──📂constants
│   │   └──📜templates.js     - 정보 공시 객체 템플릿
│   ├──📂Styled
│   │   └──📜styled.js        - 공통 css
│   └──📂utils
│       ├──📜Calendar.js      
│       ├──📜DateMaker.js
│       ├──📜SimpleCalendar.js
│       └──📜Toggle.js
├──📂components
│   ├──📂Benefit
│   │   └──📜index.jsx        - 상품 혜택 허용 설정
│   ├──📂Delivery
│   │   └──📜index.jsx        - 상품 배송 설정
│   ├──📂Etc
│   │   └──📜index.jsx        - 기타 설정
│   ├──📂ExposureSellPeriod
│   │   ├──📜index.jsx        - 노출 및 판매기간 설정
│   │   └──📜styled.js
│   ├──📂Info
│   │   └──📜index.jsx        - 상품 기본 정보
│   ├──📂IntroImage
│   │   └──📜index.jsx        - 상품 소개 이미지
│   ├──📂Notify
│   │   ├──📂elements
│   │   │   ├──📜InformationNotice.jsx
│   │   │   └──📜MoreInfoNoti.jsx
│   │   └──📜index.jsx        - 상품 정보 고시 알림 설정
│   ├──📂Option
│   │   └──📜index.jsx        - 상품 옵션
│   └──📂RecommendImage
│       ├──📂element
│       │   └──📜ImageAttachment.jsx
│       └──📜index.jsx        - 구매자 추천 이미지
├──📜App.js
├──📜index.css
└──📜index.js
```

<br>

# ⚙️ 설치 및 시작하는 법

```
$ git clone https://github.com/wiseeee/1st-week-sirloin-task

$ cd 1st-week-sirloin-task

$ npm install

$ npm run start
```

<br>

## ✅ Git - Commit Message Convention [🔗](https://webruden.tistory.com/486)

- feat : 새로운 기능 추가 (a new feature)
- fix : 버그 수정 (a bug fix)
- docs : 문서 수정 (changes to documentation)
- style : 코드 포맷팅, 세미콜론 누락, 코드 변경이 없는 경우 (formatting, missing semi colons, etc; no code change)
- refactor : 코드 리펙토링 (refactoring production code)
- test : 테스트 코드, 리펙토링 테스트 코드 추가 (adding tests, refactoring test; no production code change)
- chore : 빌드 업무 수정, 패키지 매니저 수정 (updating build tasks, package manager configs, etc; no production code change)

<br>
