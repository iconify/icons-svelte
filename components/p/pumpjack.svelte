<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="w_x299bxb"/><path class="e5cehub1r"/><path class="i_fi9xb3v"/><path class="yj1yzfbjp"/><path class="yqjp74brx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:pumpjack" {...props}></Icon>
<style>
:global(.e5cehub1r) {
  fill: currentColor;
  d: path("M16.5 4c2.75 0 5 2.5 5 5.5h-2.25c0-1.5-1-1.75-2.75-1.75Z");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.i_fi9xb3v) {
  d: path("M11 6L8 21.5M11 6l3 15.5");
}

:global(.w_x299bxb) {
  d: path("M4.5 6h12");
}

:global(.yj1yzfbjp) {
  fill: currentColor;
  d: path("M4 12h1a1.5 1.5 0 0 1 1.5 1.5v1A1.5 1.5 0 0 1 5 16H4a1.5 1.5 0 0 1-1.5-1.5v-1A1.5 1.5 0 0 1 4 12");
}

:global(.yqjp74brx) {
  d: path("M4.5 6v6m16-2.5V18m0 0za1.5 1.5 0 0 1 1.5 1.5v.5a1.5 1.5 0 0 1-1.5 1.5A1.5 1.5 0 0 1 19 20v-.5a1.5 1.5 0 0 1 1.5-1.5M2 21.5h20");
}

</style>
