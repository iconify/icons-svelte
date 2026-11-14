<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="giz51yjgl"/><path class="xeu0br9yb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:category-ebooks" {...props}></Icon>
<style>
:global(.giz51yjgl) {
  d: path("M7.125 2h9.75A2.625 2.625 0 0 1 19.5 4.625v14.75A2.625 2.625 0 0 1 16.875 22h-9.75A2.625 2.625 0 0 1 4.5 19.375V4.625A2.625 2.625 0 0 1 7.125 2");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.xeu0br9yb) {
  d: path("M12 8.5C10.5 7.25 9 7 7.25 7v7.5c1.75 0 3.25.25 4.75 1.5c1.5-1.25 3-1.5 4.75-1.5V7C15 7 13.5 7.25 12 8.5m0 0V16m0 3h.01");
}

</style>
