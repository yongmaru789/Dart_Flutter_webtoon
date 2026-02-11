# Flutter Webtoon App Clone

노마드코더의 'Flutter로 웹툰 앱 만들기' 강의를 시청하며 학습한 프로젝트입니다.

## Key Learning
1. API Data Fetching 
2. 비동기 UI 렌더링 (FutureBuilder)
3. 화면 전환 및 데이터 전달 (Navigator)
4. 데이터 저장 (Shared Preferences)

## Trouble Shooting
문제 : API에서 제공하는 이미지가 특정 브라우저 외에서 호출할 때 403 Forbidden 에러 발생  
해결 : NetworkImage 호출 시 header에 특정 User-Agent 값을 추가하여 접근 권한 문제 해결

