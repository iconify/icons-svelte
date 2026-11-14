<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qe97cg-lx"/><path class="gdom51bcy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:parking-occupancy-chart" {...props}></Icon>
<style>
:global(.gdom51bcy) {
  d: path("M7.5 11V3.5h2.25a2.25 2.25 0 0 1 0 4.5H7.5m2 9.5v-3.25M14 17.5V10m4.5 7.5v-12");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.qe97cg-lx) {
  d: path("M3 3v18h18");
}

</style>
