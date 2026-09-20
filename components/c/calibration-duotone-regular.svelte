<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="jlgxzd_ny"/><path class="b842d4b5v"/><path class="gb7yzvvzz"/><path class="q1h6kybti"/><path class="qe97cg-lx"/><path class="bd3-a5q0s"/><path class="c4o3x9bhp"/><path class="w9g5wtasy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:calibration-duotone-regular" {...props}></Icon>
<style>
:global(.b842d4b5v) {
  fill: currentColor;
  d: path("M14 15a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.bd3-a5q0s) {
  d: path("M6 18 18 6");
}

:global(.c4o3x9bhp) {
  d: path("M8 9a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.gb7yzvvzz) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 3v18h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.jlgxzd_ny) {
  fill: currentColor;
  d: path("M8 9a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.q1h6kybti) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M6 18 18 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.qe97cg-lx) {
  d: path("M3 3v18h18");
}

:global(.w9g5wtasy) {
  d: path("M14 15a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

</style>
