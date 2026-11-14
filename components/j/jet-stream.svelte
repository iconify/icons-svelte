<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="yt4ihub-r"/><path class="yyjzt3bvb"/><path class="gey0goydo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:jet-stream" {...props}></Icon>
<style>
:global(.gey0goydo) {
  d: path("M2.5 18.5q7.5-6 15-1.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.yt4ihub-r) {
  d: path("M5.25 9.5q8.25-7 16.25-1");
}

:global(.yyjzt3bvb) {
  d: path("M2.5 14q8.5-7 17-1");
}

</style>
