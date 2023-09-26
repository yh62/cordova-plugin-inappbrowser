### # 코드 수정된 경로

> cordova-plugin-inappbrowser/src/android/InAppBrowser.java


### # 비디오 전체 화면 모드일 때, 노치 부분 숨김
    781 line 구문 변경: attrs.flags |= WindowManager.LayoutParams.FLAG_LAYOUT_NO_LIMITS;
    800 line 구문 변경: attrs.flags &= ~WindowManager.LayoutParams.FLAG_LAYOUT_NO_LIMITS;


### # 비디오 전체 화면 모드 실행 후.. 북마크 Input 태그에 포커스 안되는 현상 해결
    807 lien 구문 추가: inAppWebView.clearFocus();


### # 비디오 전체 화면 모드 실행 후.. 화면 전환이 안되는 현상 해결
    1034 lien 구문 변경: activity.setRequestedOrientation(ActivityInfo.SCREEN_ORIENTATION_UNSPECIFIED);
    

출처 링크 - [inappbrowser-with-fullscreen-video](https://github.com/The-White-Fang/cordova-plugin-inappbrowser/tree/inappbrowser-with-fullscreen-video)
