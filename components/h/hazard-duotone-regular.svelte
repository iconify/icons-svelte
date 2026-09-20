<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ipb1x_bvt"/><path class="wno2bb6wt"/><path class="sscby3y4w"/><path class="mapwwf30m"/><path class="vqi6vft7m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:hazard-duotone-regular" {...props}></Icon>
<style>
:global(.ipb1x_bvt) {
  fill: currentColor;
  d: path("m12 2.5 9.5 9.5 -9.5 9.5L2.5 12Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.mapwwf30m) {
  d: path("M12 7v4.5");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.sscby3y4w) {
  d: path("m12 2.5 9.5 9.5 -9.5 9.5L2.5 12Z");
}

:global(.vqi6vft7m) {
  d: path("M11 15.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.wno2bb6wt) {
  fill: currentColor;
  d: path("M11 15.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
