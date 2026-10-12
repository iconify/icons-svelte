<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="b5iy4umwa"/><rect class="k-jom-byp"/><circle class="cvk--017m"/><path class="d7e32ebyd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:privacy-lock" {...props}></Icon>
<style>
:global(.b5iy4umwa) {
  d: path("M8 10.25V7.5a4 4 0 0 1 8 0v2.75");
}

:global(.cvk--017m) {
  cx: 12px;
  cy: 14.25px;
  r: 1.5px;
}

:global(.d7e32ebyd) {
  d: path("M9.5 18.5a2.5 2.5 0 0 1 5 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.k-jom-byp) {
  width: 15.5px;
  height: 11px;
  x: 4.25px;
  y: 10.25px;
  rx: 3px;
}

</style>
