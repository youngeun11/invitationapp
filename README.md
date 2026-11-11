# 2026 한국해양대학교 아치대동제 초청장 앱

[축제 초청장 사이트](https://youngeun11.github.io/party/)를 전체 화면 WebView로 보여주는 Android 앱입니다.

안드로이드 스튜디오 없이 GitHub Actions로 APK를 빌드할 수 있습니다.

## GitHub Actions로 APK 받기

1. 이 저장소를 GitHub에 올립니다.
2. **Actions** 탭에서 `Build Android APK` 워크플로가 끝날 때까지 기다립니다. 처음 푸시하면 자동 실행됩니다.
3. 완료된 워크플로를 연 뒤 **Artifacts**에서 다음 파일을 받습니다.
   - `archfest-debug`
   - `archfest-release` (디버그 키로 서명되어 바로 설치 가능)
4. 압축을 풀고 휴대폰에 `app-debug.apk` 또는 `app-release.apk`를 설치합니다.

수동으로 다시 빌드하려면 Actions에서 `Build Android APK` → **Run workflow**를 선택하면 됩니다.

## 앱 정보

- 패키지: `kr.ac.kmou.archfest`
- 표시 이름: 아치대동제
- 최소 SDK: 24 (Android 7.0)
- 대상 URL: `https://youngeun11.github.io/party/`
