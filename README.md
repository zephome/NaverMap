# 네이버맵 샘플 코드

## 키 발급 방법
- URL: http://developer.naver.com/wiki/pages/OpenAPI
- key 발급 시 허용할 URL을 입력하기때문에 key는 반드시 발급받아야 함 (아래 key는 localhost:10003만 사용할 수 있음)
- `<script type="text/javascript" src="http://openapi.map.naver.com/openapi/naverMap.naver?ver=2.0&key=키입력"></script>`

## 주소를 좌표로 변환
1. http://map.naver.com/
2. 주소 검색
3. 위치가 지도에 표시되면 마커 클릭
4. 상세정보 창이 나오면 보내기 버튼 클릭
5. URL 복사 클릭
6. 주소에서 Lat(x), Lng(y) 값 입력 (index.html Line. 25): var oCenterPoint = new nhn.api.map.LatLng(Lat, Lng);
