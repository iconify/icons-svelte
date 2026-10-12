<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="cc4g6ccbh"/><rect class="wbemmcbwu"/><rect class="gln1_k_7d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:pagination" {...props}></Icon>
<style>
:global(.cc4g6ccbh) {
  d: path("m4.25 10l-1.5 2l1.5 2m15.5-4l1.5 2l-1.5 2");
}

:global(.gln1_k_7d) {
  width: 4px;
  height: 4px;
  x: 13.25px;
  y: 10px;
  rx: 1.25px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.wbemmcbwu) {
  width: 4px;
  height: 4px;
  x: 6.75px;
  y: 10px;
  rx: 1.25px;
}

</style>
