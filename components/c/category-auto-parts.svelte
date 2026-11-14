<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="oy9aotbsd"/><path class="nwrftd82o"/><path class="vwl52ubwq"/><path class="x9z3htbyn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:category-auto-parts" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.nwrftd82o) {
  d: path("M5.5 12a6.5 6.5 0 1 0 13 0a6.5 6.5 0 1 0-13 0");
}

:global(.oy9aotbsd) {
  d: path("M2.5 12a9.5 9.5 0 1 0 19 0a9.5 9.5 0 1 0-19 0");
}

:global(.vwl52ubwq) {
  d: path("M10.5 12a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0");
}

:global(.x9z3htbyn) {
  fill: currentColor;
  d: path("M8.25 9a.75.75 0 1 0 1.5 0a.75.75 0 1 0-1.5 0m6 0a.75.75 0 1 0 1.5 0a.75.75 0 1 0-1.5 0m-6 6a.75.75 0 1 0 1.5 0a.75.75 0 1 0-1.5 0m6 0a.75.75 0 1 0 1.5 0a.75.75 0 1 0-1.5 0");
}

</style>
