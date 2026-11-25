# 교육사업관리시스템

행복황촌협동조합 교육사업 관리용 웹앱 (index.html 한 파일).

## 공유 설정 (Firebase)
1. Firebase 콘솔 > 새 프로젝트 > Realtime Database 만들기
2. 규칙 탭에 `database.rules.json` 내용을 붙여넣고 게시
3. 앱 설정 > 서버 주소에 데이터베이스 주소(https://…firebaseio.com 또는 …firebasedatabase.app),
   접근키에 12자 이상 영문·숫자(직접 정함, 모든 기기에서 같은 값), 작업자 이름 입력 후 "서버 공유 모드로 전환"
