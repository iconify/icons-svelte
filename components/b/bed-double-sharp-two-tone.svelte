<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="aqa72m1-n"/><path class="ka6ebhzpv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:bed-double-sharp-two-tone" {...props}></Icon>
<style>
:global(.aqa72m1-n) {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M1 20L1 11C1 10.4477 1.4477 10 2 10L4 10L4 4C4 3.4477 4.4477 3 5 3L19 3C19.5523 3 20 3.4477 20 4L20 10L22 10C22.5523 10 23 10.4477 23 11L23 20C23 20.5523 22.5523 21 22 21L2 21C1.4477 21 1 20.5523 1 20Z");
  stroke: none;
}

:global(.gp_8x1bzb) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.ka6ebhzpv) {
  d: path("M2 11L22 11L22 20L2 20L2 11ZM5 11L5 4L19 4L19 11M2 15L22 15M12 11L12 15");
}

</style>
