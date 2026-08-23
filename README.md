# 현종 포트폴리오 (congchu/web-porfolio 기반)

congchu/web-porfolio 템플릿을 기반으로, 신입 개발자에게 불필요한 부분(가짜 통계, Work Experience, Side Projects, Blog, lorem ipsum 항목)을 제거하고 실제 내용으로 채운 버전입니다.

## 이 템플릿에서 뺀 것
- 코딩한 일수 / Happy Customers / Cups of coffee 같은 가짜 통계 섹션
- Work Experience 탭 (신입이라 경력 없음)
- Skills의 중복 원형 그래프 (막대 그래프만 유지)
- Side Projects 그리드, Blog 섹션 (원 제작자의 실제 프로젝트/글이라 그대로 쓸 수 없음)
- Projects 탭에 섞여 있던 lorem ipsum 수상 경력 항목
- 이력서 다운로드 버튼 (연결할 파일이 없어서)

## 남긴 것 + 채운 내용
- Home(히어로), About, Education(KH정보교육원 수료, 정보처리기사 필기), Skills(Java/Spring Boot/MyBatis/Oracle/React/JavaScript), Projects(UNIVOL, 청년복지 MOA), 구직 CTA 배너, Contact

## 배포 방법
1. GitHub에 새 저장소를 만듭니다.
2. 이 폴더 전체를 push 합니다.
3. Settings > Pages에서 Source를 `main` / `root`로 지정합니다.
4. 몇 분 뒤 배포된 URL로 확인합니다.

## 바꿔야 할 것
- `images/about.jpg` → 본인 사진으로 교체 (같은 파일명으로 덮어쓰면 코드 수정 불필요)
- `index.html`의 About/Contact 영역: 이메일·전화번호·GitHub 주소를 실제 정보로 교체
- Skills 퍼센트: `index.html`의 `aria-valuenow`, `style="width:__%"` 값을 본인 숙련도에 맞게 조정
- 학력/자격증/프로젝트 설명은 실제 이력서 기준으로 다시 한 번 확인해서 다듬기

## 라이선스 안내
이 템플릿은 CC BY 3.0으로 배포되며, 하단 footer의 "Colorlib" 링크는 라이선스 조건상 제거할 수 없습니다.
