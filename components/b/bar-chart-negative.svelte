<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ijs0p36kx"/><rect class="r8c2t65yh"/><rect class="trw0bvood"/><rect class="ud8_d0biv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:bar-chart-negative" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ijs0p36kx) {
  d: path("M2.75 12h18.5");
}

:global(.r8c2t65yh) {
  width: 3.5px;
  height: 4.5px;
  x: 4.25px;
  y: 5.25px;
  rx: 1px;
}

:global(.trw0bvood) {
  width: 3.5px;
  height: 7px;
  x: 10.25px;
  y: 14.25px;
  rx: 1px;
}

:global(.ud8_d0biv) {
  width: 3.5px;
  height: 7px;
  x: 16.25px;
  y: 2.75px;
  rx: 1px;
}

</style>
