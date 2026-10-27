# Pirate Defense — 애니메이션 적용본

압축을 모두 풀고 `실행.cmd`를 실행하세요. 실행 파일과 assets 폴더를 함께 두어야 합니다.

플레이어 5종, 일반 적 6종, 승선 적, 보스 6종에 상태 기반 스프라이트 모션을 연결했습니다. 기존 로직과 이미지 파일은 변경하지 않았습니다. 자세한 구현 방식과 검증 범위는 `애니메이션_검수보고.md`를 참고하세요.

빌드: Visual Studio 2022, SFML 3.1.0 (`C:\SFML\SFML-3.1.0`), Release / x64. Windows 맑은 고딕 사용.
검사: `AnimationQA.vcxproj`는 Debug / x64에서 assertion 검사와 캡처를 실행합니다. `AnimationPerf.vcxproj`는 Release / x64용 렌더 성능 검사입니다. 실행 작업 디렉터리는 assets가 있는 프로젝트 루트여야 합니다.

미리보기와 검수 캡처는 구성된 테스트 상태를 실제 렌더러로 그린 결과이며 실전 멀티플레이 녹화가 아닙니다.
