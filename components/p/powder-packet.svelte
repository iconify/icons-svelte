<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ig3ajobdn"/><path class="ijla-ebtb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:powder-packet" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ig3ajobdn) {
  d: path("m5 5l1.75-2L8.5 5l1.75-2L12 5l1.75-2l1.75 2l1.75-2L19 5v14a2.5 2.5 0 0 1-2.5 2.5h-9A2.5 2.5 0 0 1 5 19Zm0 3h14");
}

:global(.ijla-ebtb) {
  d: path("M8 17.5q4-6 8 0Z");
}

</style>
