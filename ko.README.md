<div align="center">

<img src=".github/banner.png" alt="요정과 초록색 잔디 칸, 그리고 옥토캣" width="640">

# 잔디요정

GitHub Actions를 사용해서 매일 GitHub 잔디를 심어주는 작은 요정입니다.

[![Fairy](https://github.com/zeikar/fairy-of-grass/actions/workflows/main.yml/badge.svg)](https://github.com/zeikar/fairy-of-grass/actions/workflows/main.yml)

[English](README.md) · **한국어**

</div>

## 잔디요정 키우기

1. **Use this template** 버튼으로 내 저장소를 만듭니다. ([Docs](https://docs.github.com/ko/repositories/creating-and-managing-repositories/creating-a-repository-from-a-template#creating-a-repository-from-a-template))
2. **Settings → Secrets and variables → Actions**에서 `USER_EMAIL`이라는 이름으로 GitHub 계정 이메일을 추가합니다. ([Docs](https://docs.github.com/ko/actions/how-tos/write-workflows/choose-what-workflows-do/use-secrets#creating-secrets-for-a-repository))
3. 완료! 예쁘게 키우시길 바랍니다.

## 하는 일

매일 12:00 UTC(한국 시간 밤 9시)쯤 요정이 일어나서 GitHub 프로필에 잔디를 심어줍니다. 빈 커밋이라 바뀌는 코드는 한 줄도 없습니다. 그래도 잔디는 초록색입니다.

시간을 바꾸고 싶다면 [`.github/workflows/main.yml`](.github/workflows/main.yml)의 `cron` 값을 수정하세요.
