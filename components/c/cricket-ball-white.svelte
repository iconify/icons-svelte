<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="oy9aotbsd"/><path class="b0bwkxgvh"/><path class="cwuu6d1dz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:cricket-ball-white" {...props}></Icon>
<style>
:global(.b0bwkxgvh) {
  d: path("M21 8.75A15.5 15.5 0 0 0 8.75 21");
}

:global(.cwuu6d1dz) {
  d: path("M19.5 6.25A18.5 18.5 0 0 0 6.25 19.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.oy9aotbsd) {
  d: path("M2.5 12a9.5 9.5 0 1 0 19 0a9.5 9.5 0 1 0-19 0");
}

</style>
