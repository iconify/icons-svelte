<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="sznc3hbok"/><path class="s6-dw5boq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:advance-stop-line" {...props}></Icon>
<style>
:global(.s6-dw5boq) {
  d: path("M6.5 13.25h4l-2-4.5m-1 0h2m1 4.5l4-4.5l3 4.5m-3-4.5L14 7h1.5m-13 10h19");
}

:global(.sznc3hbok) {
  d: path("M2.75 13.25a3.75 3.75 0 1 0 7.5 0a3.75 3.75 0 1 0-7.5 0Zm11 0a3.75 3.75 0 1 0 7.5 0a3.75 3.75 0 1 0-7.5 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
