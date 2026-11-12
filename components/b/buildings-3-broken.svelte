<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="xpzbxokqs"/><path class="z-dxw3bya"/><path class="x-21zwayg"/><path class="zrnmzybnf"/><path class="n7r5ojbow"/><path class="e2mod1bzc"/><path class="ezpcs5bst"/><path class="rt6vrtimr"/><path class="r2esonbhs"/><path class="xoe9r9bui"/><circle class="lxdf-tbmp"/><path class="suhy-dbax"/><path class="cchpq1djo"/><path class="oyv2qxbiz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:buildings-3-broken" {...props}></Icon>
<style>
:global(.cchpq1djo) {
  d: path("M6.5 8C5.09554 8 4.39331 8 3.88886 8.33706C3.67048 8.48298 3.48298 8.67048 3.33706 8.88886C3 9.39331 3 10.0955 3 11.5V16M3 20V22");
}

:global(.e2mod1bzc) {
  d: path("M5.5 14H7");
}

:global(.ezpcs5bst) {
  d: path("M17 11H18.5");
}

:global(.ipq1z-bjh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.lxdf-tbmp) {
  cx: 12px;
  cy: 7px;
  r: 2px;
}

:global(.n7r5ojbow) {
  d: path("M5.5 11H7");
}

:global(.oyv2qxbiz) {
  d: path("M10 15H10.5M12.5 15H14");
}

:global(.r2esonbhs) {
  d: path("M5.5 8H7");
}

:global(.rt6vrtimr) {
  d: path("M17 14H18.5");
}

:global(.suhy-dbax) {
  d: path("M17.5 8C18.9045 8 19.6067 8 20.1111 8.33706C20.3295 8.48298 20.517 8.67048 20.6629 8.88886C21 9.39331 21 10.0955 21 11.5M21 15.5V22");
}

:global(.x-21zwayg) {
  d: path("M12 22V19");
}

:global(.xoe9r9bui) {
  d: path("M17 8H18.5");
}

:global(.xpzbxokqs) {
  d: path("M22 22L2 22");
}

:global(.z-dxw3bya) {
  d: path("M17 22V6C17 4.11438 17 3.17157 16.4142 2.58579C15.8284 2 14.8856 2 13 2H11C9.11438 2 8.17157 2 7.58579 2.58579C7 3.17157 7 4.11438 7 6V22");
}

:global(.zrnmzybnf) {
  d: path("M10 12H14");
}

</style>
