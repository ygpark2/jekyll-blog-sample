---
layout: page
title: Home
tagline: Supporting tagline
weight: 1
group: navigation
---
{% include JB/setup %}

# 우리 가족과 나의 이야기

---------------------------------------

## 저희 가족 소개

    - 나 박영규
    - 아인이 엄마 임선주
    - 우리 사랑 스런 아들 박아인

## 매일 할 일

    1. 매일 108배 하기
    2. 알아 차림 명상
    3. 스트레칭, 하이킥 연습
    4. 개인 프로젝트 사이트 개발

## 이번달 할 일

    1. 개인 프로젝트 사이트 오픈
    2. 통계 공부
    3. 글 쓰기 연습

## 올해 할 일

    1. 나의 개인 프로젝트 사이트 오픈하기
    2. 통계 공부
    3. 글 쓰기 연습

## 블로그 글 모음.

<ul class="posts">
  {% for post in site.posts %}
    {% if post.published %}
      <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
    {% endif %}
  {% endfor %}
</ul>

## 사야할 물건들

    * 아마존 킨들
    * 아이패드
    * 아이폰
    * 프린터
