---
layout: post
title: "First Content"
author: "YeonJunRhee"
---

이 블로그는 내가 한 일에 대한 기록을 남기고자 시작한다.

그런데 블로그가 github를 이용해서 만든 블로그 이기 떄문에 github나 MarkDown 문서 작성법도 나중에 배운 후에 작성을 해야 할 것 같다.

매일 배운 내용을 문서로 정리하는 방식이 되도록 습관을 들이고자 하는 목적도 있음.

그래서 우선 **github로 블로그 만들기**를 하면서 배우게 된 내용을 작성해본다.

# github로 블로그 만들기

1. [github.com](https://github.com) 사이트 접속해서 회원가입 한다.

2. 'repositories' 생성한다.
* 'repositories' 생성시 이름을 **username.github.io** 식으로 설정

3. [pages.github.com](https://pages.github.com/) 사이트 참조해서 PC에 저장소 복제를 하고 파일 추가한다.
* terminal 에서 입력한다.
* git clone https://github.com/username/username.github.io
* cd username.github.io
* echo "hello world" > index.html
* git add --all
* git commit -m "add에 대한 설명"
* git push -u origin master<br>
git push **username** master
* 브라우저에서 'https://username.github.io' 접속
* 이후 변경사항확인 = git status

4. [구글](https://www.google.com) 에서 '**jekyll theme**' 검색해서 맘에 드는 테마 다운로드한 후 PC에 저장소 복제한 폴더에 다운로드한 테마 파일을 압축해제한 후 복사한다.
* 다운로드한 테마파일 압축해제
* terminal 에서 복제한 저장소 폴더까지 들어간 후에 압축해제한 폴더 절대경로를 입력해서 복사한다.(숨김파일까지)<br>
cp -r ~/Desktop/.../테마파일폴더/ ./

5. 복사한 테마에 맞는 markdown 형식으로 블로그 작성해서 올린다.
* post에서 첫번째글 'Example Content' 참조
