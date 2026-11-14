<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="bklqkib-s"/><path class="w1nv5b9vq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:display-table" {...props}></Icon>
<style>
:global(.bklqkib-s) {
  d: path("M2.5 12h19v2.5h-19Zm2 2.5v7m15-7v7M6 8.5h12V12H6ZM6 5h12v3.5H6Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.w1nv5b9vq) {
  d: path("M10.25 5L12 6.75L13.75 5M8.5 5v3.5m7-3.5v3.5");
}

</style>
