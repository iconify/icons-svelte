<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="sxlo5xbvt"/><path class="w8uwnqmmg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:panels-right-bottom-sharp-fill" {...props}></Icon>
<style>
:global(.gp_8x1bzb) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.sxlo5xbvt) {
  fill: currentColor;
  d: path("M15 3L21 3L21 21L15 21L15 3Z");
  stroke: none;
}

:global(.w8uwnqmmg) {
  d: path("M3 3L21 3L21 21L3 21L3 3ZM15 3L15 21M15 15L3 15");
}

</style>
