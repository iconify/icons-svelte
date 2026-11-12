<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="xpzbxokqs"/><path class="z-dxw3bya"/><path class="vl-1c4b6z"/><path class="ixn1mkbma"/><path class="x-21zwayg"/><path class="zrnmzybnf"/><path class="n7r5ojbow"/><path class="e2mod1bzc"/><path class="ezpcs5bst"/><path class="rt6vrtimr"/><path class="r2esonbhs"/><path class="xoe9r9bui"/><path class="gyt9v7b_a"/><path class="ye1xc5r4d"/><path class="mbopxmbfb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:hospital-linear" {...props}></Icon>
<style>
:global(.e2mod1bzc) {
  d: path("M5.5 14H7");
}

:global(.ezpcs5bst) {
  d: path("M17 11H18.5");
}

:global(.gyt9v7b_a) {
  d: path("M10 15H14");
}

:global(.ipq1z-bjh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ixn1mkbma) {
  d: path("M3 22V8.5C3 7.09554 3 6.39331 3.33706 5.88886C3.48298 5.67048 3.67048 5.48298 3.88886 5.33706C4.39331 5 5.09554 5 6.5 5");
}

:global(.mbopxmbfb) {
  stroke-linejoin: round;
  d: path("M14 7L10 7");
}

:global(.n7r5ojbow) {
  d: path("M5.5 11H7");
}

:global(.r2esonbhs) {
  d: path("M5.5 8H7");
}

:global(.rt6vrtimr) {
  d: path("M17 14H18.5");
}

:global(.vl-1c4b6z) {
  d: path("M21 22V8.5C21 7.09554 21 6.39331 20.6629 5.88886C20.517 5.67048 20.3295 5.48298 20.1111 5.33706C19.6067 5 18.9045 5 17.5 5");
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

:global(.ye1xc5r4d) {
  stroke-linejoin: round;
  d: path("M12 9V5");
}

:global(.z-dxw3bya) {
  d: path("M17 22V6C17 4.11438 17 3.17157 16.4142 2.58579C15.8284 2 14.8856 2 13 2H11C9.11438 2 8.17157 2 7.58579 2.58579C7 3.17157 7 4.11438 7 6V22");
}

:global(.zrnmzybnf) {
  d: path("M10 12H14");
}

</style>
