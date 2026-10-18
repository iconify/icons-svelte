<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="a7s0ujb6m"/><path class="q4_xqmble"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:list-nested-sharp-two-tone" {...props}></Icon>
<style>
:global(.a7s0ujb6m) {
  stroke-opacity: 0.4;
  d: path("M8 4.5L22 4.5M10 12L22 12M12 19.5L22 19.5");
}

:global(.gp_8x1bzb) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.q4_xqmble) {
  d: path("M3 3L5 4.5L3 6ZM5 10.5L7 12L5 13.5ZM7 18L9 19.5L7 21Z");
}

</style>
