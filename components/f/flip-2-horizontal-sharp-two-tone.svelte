<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="w6c3afb2q"/><path class="jenflhpab"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:flip-2-horizontal-sharp-two-tone" {...props}></Icon>
<style>
:global(.gp_8x1bzb) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.jenflhpab) {
  d: path("M9 3L3 3L3 21L9 21M12 2L12 22M15 3L21 3L21 7M21 9.5L21 14.5M21 17L21 21L15 21");
}

:global(.w6c3afb2q) {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 3C2 2.4477 2.4477 2 3 2L9 2L9 22L3 22C2.4477 22 2 21.5523 2 21L2 3Z");
  stroke: none;
}

</style>
