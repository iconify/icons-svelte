<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="p0df1zbcw"/><path class="etf2xkbvu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:grid-2x2-plus-sharp-duotone" {...props}></Icon>
<style>
:global(.etf2xkbvu) {
  d: path("M19 15L19 23M15 19L23 19");
}

:global(.gp_8x1bzb) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.p0df1zbcw) {
  stroke-opacity: 0.4;
  d: path("M2 11L20 11L20 2L2 2L2 20L11 20L11 2");
}

</style>
