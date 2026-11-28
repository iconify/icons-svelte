<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="dxwlyvbtz"/><path class="u01l0fcal"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:inbox-arrow-down-sharp-two-tone" {...props}></Icon>
<style>
:global(.dxwlyvbtz) {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M23 13L23 20C23 20.5523 22.5523 21 22 21L2 21C1.4477 21 1 20.5523 1 20L1 13L8 13L10 16L14 16L16 13Z");
  stroke: none;
}

:global(.gp_8x1bzb) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.u01l0fcal) {
  d: path("M18.6025 6.6133L22 12.1534L22 20L2 20L2 12.1534L5.3975 6.6133M2 13L8 13L10 16L14 16L16 13L22 13M12 3L12 11M8.7071 7.7071L12 11L15.2929 7.7071");
}

</style>
