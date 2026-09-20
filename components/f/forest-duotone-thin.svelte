<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dmi31p3-b"/><path class="g5sm_rqnz"/><path class="uiny5bqrt"/><path class="dhtxwjb8m"/><path class="x9f8wob1r"/><path class="wyx0j3bin"/><path class="bos0j4biy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:forest-duotone-thin" {...props}></Icon>
<style>
:global(.bos0j4biy) {
  d: path("M3 21h18");
}

:global(.dhtxwjb8m) {
  d: path("m2 13 5 -5 5 5Z");
}

:global(.dmi31p3-b) {
  fill: currentColor;
  d: path("m2 13 5 -5 5 5Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.g5sm_rqnz) {
  fill: currentColor;
  d: path("m10 10 6 -6 6 6Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.uiny5bqrt) {
  fill: currentColor;
  d: path("m7 18 5 -5 5 5Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.wyx0j3bin) {
  d: path("m7 18 5 -5 5 5Z");
}

:global(.x9f8wob1r) {
  d: path("m10 10 6 -6 6 6Z");
}

</style>
