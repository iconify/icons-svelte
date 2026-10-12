<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="wony-7bua"/><path class="iu19jrz5q"/><circle class="upu83lbfh"/><path class="pf6jjjzym"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:bug-bounty" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.iu19jrz5q) {
  d: path("M7 6.25a2.25 2.25 0 0 1 4.5 0M5 10H2.75M5 13.5H2.75M13.5 10h2.25m-6.5-.5v6");
}

:global(.pf6jjjzym) {
  d: path("M18.25 15.5H16.5a.75.75 0 0 0 0 1.5h1a.75.75 0 0 1 0 1.5h-1.75M17 14.75v.75m0 3v.75");
}

:global(.upu83lbfh) {
  cx: 17px;
  cy: 17px;
  r: 4.25px;
}

:global(.wony-7bua) {
  width: 8.5px;
  height: 11px;
  x: 5px;
  y: 6.25px;
  rx: 4.25px;
}

</style>
