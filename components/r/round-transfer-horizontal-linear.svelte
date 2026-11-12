<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><circle class="shu3xdl9q"/><path class="cavrtqb0h"/><path class="yvp5mpkiq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:round-transfer-horizontal-linear" {...props}></Icon>
<style>
:global(.cavrtqb0h) {
  stroke-linejoin: round;
  d: path("M17 10L7 10L10.4375 7");
}

:global(.ipq1z-bjh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.shu3xdl9q) {
  cx: 12px;
  cy: 12px;
  r: 10px;
}

:global(.yvp5mpkiq) {
  stroke-linejoin: round;
  d: path("M7 14L17 14L13.5625 17");
}

</style>
