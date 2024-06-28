# react-gift-react-foundation
FE 카카오 선물하기 1주차 과제: React 기초

### Step1 요구사항
- Create React App을 기반으로 프로젝트를 생성한다.
- Typescript로 프로젝트가 동작되게 세팅한다.
- 절대 경로로 Import 할 수 있게 alias를 설정한다.
- tsconfig에 어떤 항목들로 구성되어 있는지 살펴보고, 필요하다 생각되는 설정을 설정한다.
- ESLint, Prettier를 추가하고 Airbnb룰을 설정한다.
- emotion 스타일 라이브러리를 추가하고, reset css를 적용한다.
- gitignore를 추가하고, 프로젝트에 불필요한 코드들을 정리한다.
- 본인만의 폴더 구조 기준을 세우고 반영한다.
- 본인만의 기준으로 일관된 코드를 작성한다.
- 기능 단위로 나누어 커밋한다.

### Step2 요구사항
- 본인만의 기준으로 일관된 코드를 작성한다.
- 기능 단위로 나누어 커밋한다.
- Stroybook을 추가한다.
- 공통 컴포넌트에 아래와 같은 컴포넌트를 구현하고, Storybook에서 확인 할 수 있게 한다. 
    - Button 컴포넌트를 구현한다.
        - Theme Props에 따라 버튼의 컬러와 디자인이 다르게 보여지게 한다.
        - Size Props에 따라 버튼의 Size가 다르게 보여지게 한다. (value가 responsive 인 경우 미디어 쿼리에 따라 사이즈가 달라지게 만든다.)
        - Button Element의 기본 속성들을 모두 사용할 수 있게 한다.
    - Input 컴포넌트를 구현한다.
        - disabled Props에 따라 Input이 비활성화 되고, UI에서도 비활성화 됨을 인지할 수 있게 한다.
        - invalid Props 에 따라 Input의 값이 잘 못되었음을 UI에서 인지할 수 있게 한다.
        - Size Props에 따라 버튼의 Size가 다르게 보여지게 한다. (value가 responsive 인 경우 미디어 쿼리에 따라 사이즈가 달라지게 만든다.)
        - Input Element의 기본 속성들을 모두 사용할 수 있게 한다.
    - Image 컴포넌트를 구현한다.
        - ratio Props에 따라 이미지 비율을 설정할 수 있게 한다. (value가 number로 16/9로 넘겨진 경우 16:9비율로 보여짐, square을 설정한 경우 정사각형으로 보여짐)
        - radius Props에 따라 모서리가 둥글게 한다. (value가 number인 경우 number만큼 모서리가 둥글게 적용, circle인 경우 원형으로 보여짐)
        - Img Element의 기본 속성들을 모두 사용할 수 있게 한다.
    - GoodsItem 컴포넌트를 구현한다.
        - Default 형태와 Ranking 형태의 컴포넌트를 각각 구현한다.
        - 공통으로 imageSrc, subtitle, title, amount Props를 넘겨받는다.
        - Ranking 컴포넌트의 경우 rankingIndex Props를 추가로 넘겨받는다. 1~3까지는 분홍색, 나머지 숫자에는 회색의 랭킹 뱃지가 보여지게 한다.
        - Grid, Container 컴포넌트를 구현한다.