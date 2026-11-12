<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><circle class="shu3xdl9q"/><path class="nub2oubsa"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:round-alt-arrow-right-linear" {...props}></Icon>
<style>
:global(.ipq1z-bjh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.nub2oubsa) {
  stroke-linejoin: round;
  d: path("M10.5 9L13.5 12L10.5 15");
}

:global(.shu3xdl9q) {
  cx: 12px;
  cy: 12px;
  r: 10px;
}

</style>
