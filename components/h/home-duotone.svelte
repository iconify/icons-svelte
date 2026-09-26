<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="jxujf_bem"/><path class="wr1z0cbrp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:home-duotone" {...props}></Icon>
<style>
:global(.jxujf_bem) {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M10.0605 2.70707C11.1795 1.7591 12.8205 1.7591 13.9395 2.70707L20.9395 8.63773L21.0615 8.74808C21.6586 9.31297 22 10.1002 22 10.9268V19C21.9999 20.6568 20.6568 22 19 22H5C3.34318 22 2.00011 20.6568 2 19V10.9268C2.00002 10.0452 2.38775 9.20775 3.06055 8.63773L10.0605 2.70707Z");
  stroke: none;
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.wr1z0cbrp) {
  d: path("M9 21L9 14L15 14L15 21");
}

</style>
