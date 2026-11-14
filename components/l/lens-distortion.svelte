<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="y0jea7f2k"/><path class="hq5e0hzjl"/><path class="mhrzs30pu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:lens-distortion" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.hq5e0hzjl) {
  d: path("M9.5 4q-1 8 0 16m5-16q1 8 0 16");
}

:global(.mhrzs30pu) {
  d: path("M4 9.5q8-1 16 0m-16 5q8 1 16 0");
}

:global(.y0jea7f2k) {
  d: path("M5 5q7-2.5 14 0q2.5 7 0 14q-7 2.5-14 0q-2.5-7 0-14");
}

</style>
