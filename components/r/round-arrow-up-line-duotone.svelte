<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><circle class="doy9q4b5f"/><path class="vyf6m7_ke"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:round-arrow-up-line-duotone" {...props}></Icon>
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

:global(.vyf6m7_ke) {
  stroke-linejoin: round;
  d: path("M12 16L12 8M9 11L12 8L15 11");
}

</style>
