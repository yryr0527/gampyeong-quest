# 감평 QUEST v1
개인용 PWA 타이쿤. 가상 수임료는 실제 돈이 아닙니다.
## 실행
압축을 풀고 index.html을 열면 기본 게임을 실행할 수 있습니다(브라우저별 로컬 저장 제한 가능).
PC에서 Python 설치 후 이 폴더에서 `python -m http.server 8000` 실행, http://localhost:8000 접속.
## 스마트폰 설치
GitHub Pages 등 HTTPS 정적 호스팅에 폴더 안의 파일 전체를 배포합니다. GitHub에서 새 저장소 생성 → 파일 업로드 → Settings → Pages → Deploy from a branch → main / root → Save. 발급된 HTTPS 주소를 Android Chrome에서 열고 메뉴 → 홈 화면에 추가 또는 앱 설치. iOS Safari는 공유 → 홈 화면에 추가. 최초 온라인 접속 후 서비스워커 캐시가 완료되면 오프라인 이용 가능.
## 데이터
18개 예시 문제. 최신 법령 원문 검증 전이며 기출문제가 아닙니다. 관리 화면에서 문제를 직접 추가하고 JSON 백업/복원 가능. 브라우저별 저장소는 별개이며 서버 동기화 없음. AI 채점 미구현.
