<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="dxdxrabbj"/><path class="eshr8umxs"/><path class="dz69gvw-b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:repost-undo" {...props}></Icon>
<style>
:global(.dxdxrabbj) {
  d: path("M3.5 10.5V7a2 2 0 0 1 2-2h10");
}

:global(.dz69gvw-b) {
  d: path("M16.75 15.25L15 17l1.75 1.75");
}

:global(.eshr8umxs) {
  d: path("M13 2.5L15.5 5L13 7.5m2.5 2.5v2.5q0 .051-.003.101M12.228 14.5H3.5M6 12l-2.5 2.5L6 17m10.5 4.5H19a2.25 2.25 0 0 0 0-4.5h-4");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
