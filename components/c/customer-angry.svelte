<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="f_cffe73u"/><path class="nq2i17p9o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:customer-angry" {...props}></Icon>
<style>
:global(.f_cffe73u) {
  d: path("M5.5 9a6.5 6.5 0 1 0 13 0a6.5 6.5 0 1 0-13 0m-2 12.5c0-2 3.75-3.25 8.5-3.25s8.5 1.25 8.5 3.25M8.75 7.25l2 1m4.5-1l-2 1");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.nq2i17p9o) {
  d: path("M10 12.5q2-1.5 4 0");
}

</style>
