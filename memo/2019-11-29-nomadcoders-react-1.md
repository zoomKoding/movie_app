---
title: (웹다시개발) 노마드코더스 ReactJS로 웹 서비스 만들기 중심 내용 정리
layout: post
date: '2019-11-29 02:00:00'
author: 줌코딩
tags: nomadcoders react
cover: "/assets/instacode.png"
categories: react web개발
---

## React의 역할

Javascript로 작성된 요소들을 HTML로 변환해서 HTML에 밀어넣어준다.

## React가 빠른 이유

React는 소스코드에 처음부터 HTML을 넣지 않고 HTML에서 HTML을 추가하거나 제거하는 방법을 알고있다.

빈 HTML을 로드하고 react가 HTML을 밀어넣게 된다.

이것을 virtual DOM이라고 한다.
virtual인 이유는 실제 html 코드 상에 존재하지 않는 것을 react가 만들어서 넣어준 것이다. 그래서 html 코드에는 존재하지 않는다.

## React Component

React는 다 컴포넌트로 구성되어 있다.
컴포넌트는 html을 return하는 함수이다.
react는 component를 사용해서 HTML처럼 작성하려 할 때 필요하다.

이런 Javascript와 HTML의 조합을 **jsx**라고 부른다.(react에서 소개한 개념이다.) 쉽게 말해 HTML in Javascript이다.

React의 Component에 property에 해당하는 값을 전달해줄 수도 있다.
그걸 쓰기 위해서는 html에서 {}를 사용해서 받으면 된다.

Component는 무조건 대문자로 시작!

동적으로 데이터를 띄워주기 위해서는 map을 사용하면 된다.

map을 이용하면 array 가져가서 array를 이용한 무언가를 리턴한다.

**그리고 이 때 react component는 모두 달라야한다.** 이를 위해 각각의 정보에 유니크한 key값을 넣어준다. 그리고 key값을 알려줘야한다.

prop에 어떤 값이 들어왔을 때 이게 type에 맞게 들어왔는지 확인해줄 필요가 있다.

propType을 정의해주면서 데이터가 어떤식으로 들어와야하는지 type과 꼭 들어와야하는지 정할 수 있다. **이 때 이름은 반드시 propType으로 해줘야 한다.**

## React Class Component


Class component에서의 state의 의미
render 함수

state를 바꾸는 방법
setState 사용법

React Component의 life cycle을 이해하기

api
axios
async await

map 함수 사용법

responsive한 웹만들기

gh_page

react-router-dom
hash-router
browserrouter(not good for github page)
link & router
link는 반드시 router 안에 있어야 한다.
Route and Props 