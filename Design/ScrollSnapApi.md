## 스크롤 스냅 API를 이용하기

```css
.scroller {
  height: 300px;
  overflow-y: scroll;
  scroll-snap-type: y mandatory;
}

.scroll section {
  scroll-snap-align: start;
}
```

다음과 같이 이용할 수 있다.

개발을 하면 스크롤을 특정 위치에 두게 하여서 사용자가 보게끔 하면 좋겠다는 생각을 자주 하게 되는데 `scoll-snap-api`를 이용하면 그런 상상을 현실화 시키기가 매우 쉬울것 같습니다.

### 출처

[Mdn](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Scroll_Snap/Basic_concepts)
[카카오 엔터프라이즈 기술 블로그](https://fe-developers.kakaoent.com/2023/230119-scroll-snap/)
