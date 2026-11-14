<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dxdxrabbj"/><path class="m-pq4db0y"/><path class="dz69gvw-b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:repost-undo" {...props}></Icon>
<style>
:global(.dxdxrabbj) {
  d: path("M3.5 10.5V7a2 2 0 0 1 2-2h10");
}

:global(.dz69gvw-b) {
  d: path("M16.75 15.25L15 17l1.75 1.75");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.m-pq4db0y) {
  d: path("M13 2.5L15.5 5L13 7.5m2.5 2.5v2.5q0 .155-.024.308M13.529 14.5H3.5M6 12l-2.5 2.5L6 17m10.5 4.5H19a2.25 2.25 0 0 0 0-4.5h-4");
}

</style>
