<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="gs35-ps8f"/><path class="ncrpcqudc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:map-pin-check-corner-duocolor-round" {...props}></Icon>
<style>
:global(.gs35-ps8f) {
  stroke-opacity: 0.4;
  d: path("M8 9a2 2 0 1 0 4 0a2 2 0 0 0-4 0m5 8l3 3l5-6");
}

:global(.ncrpcqudc) {
  d: path("M10 21c-3-2-7-6-7-11a7 7 0 0 1 13.982-.5");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
