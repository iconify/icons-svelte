<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="g6ulkabjn"/><path class="gqsk-mblt"/><path class="sw4w7sb0q"/><path class="x_if79bzs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:depth-map" {...props}></Icon>
<style>
:global(.g6ulkabjn) {
  d: path("M2.5 2.5h19v19h-19Z");
}

:global(.gqsk-mblt) {
  d: path("M5.5 13H11v5.5H5.5Z");
}

:global(.sw4w7sb0q) {
  d: path("M8.25 13v-2.75h5.5v5.5H11");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.x_if79bzs) {
  d: path("M11 10.25V7.5h5.5V13h-2.75");
}

</style>
