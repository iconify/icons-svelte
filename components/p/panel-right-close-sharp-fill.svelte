<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="sxlo5xbvt"/><path class="pgf58j54v"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:panel-right-close-sharp-fill" {...props}></Icon>
<style>
:global(.gp_8x1bzb) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.pgf58j54v) {
  d: path("M3 3L21 3L21 21L3 21L3 3ZM15 3L15 21M7.7071 8.7071L11 12L7.7071 15.2929");
}

:global(.sxlo5xbvt) {
  fill: currentColor;
  d: path("M15 3L21 3L21 21L15 21L15 3Z");
  stroke: none;
}

</style>
