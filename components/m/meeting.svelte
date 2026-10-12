<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="ew68babsr"/><circle class="mwe-9d8rn"/><circle class="xd6dk168z"/><rect class="im1ubzb_f"/><path class="l2vfdiurs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:meeting" {...props}></Icon>
<style>
:global(.ew68babsr) {
  cx: 5.5px;
  cy: 8.75px;
  r: 2px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.im1ubzb_f) {
  width: 18.5px;
  height: 3.25px;
  x: 2.75px;
  y: 13.5px;
  rx: 1.5px;
}

:global(.l2vfdiurs) {
  d: path("M6.5 16.75v4.5m11-4.5v4.5");
}

:global(.mwe-9d8rn) {
  cx: 12px;
  cy: 5.5px;
  r: 2px;
}

:global(.xd6dk168z) {
  cx: 18.5px;
  cy: 8.75px;
  r: 2px;
}

</style>
