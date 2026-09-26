<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="vxugm2o-n"/><path class="syl-c0ccg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:fullscreen-2-sharp-two-tone" {...props}></Icon>
<style>
:global(.gp_8x1bzb) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.syl-c0ccg) {
  d: path("M11 21L3 21L3 13");
}

:global(.vxugm2o-n) {
  stroke-opacity: 0.4;
  d: path("M13 3L21 3L21 11");
}

</style>
