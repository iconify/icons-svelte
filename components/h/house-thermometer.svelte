<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="g_o3_obbf"/><path class="h2vvt1b0q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:house-thermometer" {...props}></Icon>
<style>
:global(.g_o3_obbf) {
  d: path("M13.244 20.5H3.5v-10L12 3.25l8.5 7.25v1.356");
}

:global(.h2vvt1b0q) {
  d: path("M17 18v-3a1 1 0 0 1 2 0v3a2 2 0 1 1-2 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
