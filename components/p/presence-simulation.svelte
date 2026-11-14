<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qjar_zbba"/><path class="a6k62accz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:presence-simulation" {...props}></Icon>
<style>
:global(.a6k62accz) {
  d: path("M18 16.5V18l1.25 1");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.qjar_zbba) {
  d: path("M8.213 2.5h3.574a1.75 1.75 0 0 1 1.639 1.136l1.687 4.5a1.75 1.75 0 0 1-1.638 2.364h-6.95a1.75 1.75 0 0 1-1.638-2.364l1.687-4.5A1.75 1.75 0 0 1 8.213 2.5m1.787 8v10m-3.5 0h6m2.25-2.5a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0");
}

</style>
