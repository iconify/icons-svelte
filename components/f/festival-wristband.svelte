<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ush9cxb5g"/><rect class="ahkej714i"/><path class="acelcob_j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:festival-wristband" {...props}></Icon>
<style>
:global(.acelcob_j) {
  d: path("M10.75 18.25h2.5");
}

:global(.ahkej714i) {
  width: 5.5px;
  height: 5.5px;
  x: 9.25px;
  y: 15.5px;
  rx: 1.25px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ush9cxb5g) {
  d: path("M4 11a8 4.5 0 1 0 16 0a8 4.5 0 1 0-16 0m3-.5a5 1.5 0 1 1 10 0a5 1.5 0 1 1-10 0");
}

</style>
