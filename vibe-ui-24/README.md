# Vibe UI 24 - 공개용 UI 실습 사전

HTML, CSS, JavaScript로 만든 독립형 웹페이지입니다. `index.html` 파일을 크롬, 사파리 또는 Edge에서 열면 됩니다.

## 페이지 안내

- [`index.html`](./index.html): 기존 UI 24 데모와 HTML / CSS / JavaScript 소스 보기
- [`vanilla-js.html`](./vanilla-js.html): 24가지 실습을 Vanilla JavaScript 이벤트와 DOM API로 구현한 추가 페이지. 소스 패널에 실제 실행된 `init(stage)` 함수 원문을 표시합니다.

> 두 페이지 모두 HTML/CSS로 형태를 그리고, 새 페이지는 사용자 조작·상태 변경·애니메이션 트리거를 JavaScript로 처리합니다.

## 포함된 기능

- 필수 UI 패턴 24가지와 직접 조작 가능한 데모
- 각 데모 옆 HTML / CSS / JavaScript 소스 보기 탭
- 선택 코드 복사 (현재 페이지의 실제 구현에서 추출한 부분)
- AI 프롬프트 복사, 검색, 카테고리 필터
- 데스크톱 / 태블릿 / 모바일 반응형 지원
- 서버와 외부 JS 라이브러리 불필요

## 소스 보기 안내

소스 패널은 현 페이지에서 사용한 각 데모의 마크업, 적용된 핵심 CSS 규칙, 공통 이벤트 처리 코드 일부를 보여줍니다. JavaScript 코드는 일부가 공통 함수와 공유 상태를 활용하는 발췌 코드입니다. **단독 실행용 개별 컴포넌트 파일은 아닙니다.** 전체 동작을 이해하거나 수정하려면 `index.html`의 CSS 및 script 영역을 함께 확인하세요.

## GitHub Pages 배포

기존 `woochoi/my-etc` 저장소에서 **Settings → Pages → main / (root)**를 활성화하면 이 폴더의 두 페이지를 제공할 수 있습니다.

- 기존 UI: `https://woochoi.github.io/my-etc/vibe-ui-24/`
- 순수 JS 실습: `https://woochoi.github.io/my-etc/vibe-ui-24/vanilla-js.html`

## 이용 및 개인정보

웹페이지는 오프라인에서 사용 가능하며 별도 로그인·서버 저장·개인정보 수집 기능이 없습니다. 실습 중 저장과 삭제는 화면 내에서만 재현되는 예시 동작입니다.