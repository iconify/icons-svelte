<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="eq5uxcb1m"/><path class="ubz8hc38d"/><circle class="t6u2r9bql"/><path class="de-nvpb2c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:ai-search" {...props}></Icon>
<style>
:global(.de-nvpb2c) {
  d: path("m18.4 18.4l2.85 2.85");
}

:global(.eq5uxcb1m) {
  width: 12.5px;
  height: 17px;
  x: 3.75px;
  y: 2.75px;
  rx: 2.25px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.t6u2r9bql) {
  cx: 16px;
  cy: 16px;
  r: 3.25px;
}

:global(.ubz8hc38d) {
  d: path("M7.25 7h5.5m-5.5 3.5h3.5");
}

</style>
