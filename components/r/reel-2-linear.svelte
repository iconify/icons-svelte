<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><circle class="shu3xdl9q"/><path class="pn2r-9bzq"/><path class="i46k68_po"/><path class="p8jx-kb8x"/><path class="ja8v-rhtc"/><path class="ne6lh4btq"/><path class="zbfkny6yh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:reel-2-linear" {...props}></Icon>
<style>
:global(.i46k68_po) {
  d: path("M12 9C13.6569 9 15 10.3431 15 12C15 13.6569 13.6569 15 12 15C10.3431 15 9 13.6569 9 12C9 10.3431 10.3431 9 12 9Z");
}

:global(.ipq1z-bjh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ja8v-rhtc) {
  stroke-linejoin: round;
  d: path("M18.5 12H18.5001");
}

:global(.ne6lh4btq) {
  stroke-linejoin: round;
  d: path("M12 18.5H12.0001");
}

:global(.p8jx-kb8x) {
  stroke-linejoin: round;
  d: path("M12 5.5H12.0001");
}

:global(.pn2r-9bzq) {
  d: path("M12 22L22 22");
}

:global(.shu3xdl9q) {
  cx: 12px;
  cy: 12px;
  r: 10px;
}

:global(.zbfkny6yh) {
  stroke-linejoin: round;
  d: path("M5.5 12H5.5001");
}

</style>
