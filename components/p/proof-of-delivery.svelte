<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="ddwl7oyiu"/><path class="k581ysbtm"/><circle class="upu83lbfh"/><path class="l12gfwbwm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:proof-of-delivery" {...props}></Icon>
<style>
:global(.ddwl7oyiu) {
  width: 12.5px;
  height: 18.5px;
  x: 2.75px;
  y: 2.75px;
  rx: 1.5px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.k581ysbtm) {
  d: path("M6 7h6m-6 3.5h6M6 14h3");
}

:global(.l12gfwbwm) {
  d: path("m15.25 17l1.25 1.25l2.25-2.5");
}

:global(.upu83lbfh) {
  cx: 17px;
  cy: 17px;
  r: 4.25px;
}

</style>
