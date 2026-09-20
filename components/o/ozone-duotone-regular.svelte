<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="q2rf3qbee"/><path class="ur9jjfbgq"/><path class="k-gv_lb9q"/><path class="i5be34b7d"/><path class="y0y0ccsoe"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:ozone-duotone-regular" {...props}></Icon>
<style>
:global(.i5be34b7d) {
  d: path("M13 12a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
}

:global(.k-gv_lb9q) {
  d: path("M3 12a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.q2rf3qbee) {
  fill: currentColor;
  d: path("M3 12a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.ur9jjfbgq) {
  fill: currentColor;
  d: path("M13 12a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.y0y0ccsoe) {
  d: path("M10 12h4");
}

</style>
