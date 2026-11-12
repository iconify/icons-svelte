<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><circle class="doy9q4b5f"/><path class="wbwxu-w2n"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:round-arrow-right-down-line-duotone" {...props}></Icon>
<style>
:global(.doy9q4b5f) {
  cx: 12px;
  cy: 12px;
  r: 10px;
  opacity: var(--svg-opacity--0-5, 0.5);
}

:global(.ipq1z-bjh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.wbwxu-w2n) {
  stroke-linejoin: round;
  d: path("M9 9L15 15M10.5 15L15 15L15 10.5");
}

</style>
