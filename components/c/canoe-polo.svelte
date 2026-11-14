<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wv6dgxber"/><path class="r2eszj_qo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:canoe-polo" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.r2eszj_qo) {
  d: path("M14 5q3 2.5 6 0");
}

:global(.wv6dgxber) {
  d: path("M2.5 12C5 14 8 14.5 12 14.5s7-.5 9.5-2.5c-1 5-4.5 7.5-9.5 7.5S3.5 17 2.5 12m11-5.5a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0");
}

</style>
