<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="jm4-4_b1b"/><path class="urwe8bb9z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:close-line-duotone" {...props}></Icon>
<style>
:global(.ipq1z-bjh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jm4-4_b1b) {
  d: path("M19.0068 5L5.00684 19");
  opacity: var(--svg-opacity--0-5, 0.5);
}

:global(.urwe8bb9z) {
  d: path("M19 19L5 5");
}

</style>
