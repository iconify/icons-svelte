<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="x_z33vbzn"/><path class="tiyl4eb5q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:flat-white" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.tiyl4eb5q) {
  d: path("M17 7.25h1a2.25 2.25 0 0 1 0 4.5h-1.75M3 16.5q9 3 18 0");
}

:global(.x_z33vbzn) {
  d: path("M4 6h13v3a5 5 0 0 1-5 5H9a5 5 0 0 1-5-5Z");
}

</style>
