<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="zugrvnb7t"/><path class="t-oxscctn"/><path class="j08f9ezai"/><path class="dihddo_by"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:horizon-outline-regular" {...props}></Icon>
<style>
:global(.dihddo_by) {
  d: path("M6 18h12");
}

:global(.j08f9ezai) {
  d: path("m12 13 4 -4 4 4");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.t-oxscctn) {
  d: path("m5 13 4 -4 4 4");
}

:global(.zugrvnb7t) {
  d: path("M2 13h20");
}

</style>
