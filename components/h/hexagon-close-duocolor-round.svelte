<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="tocao8blo"/><path class="m5m2x9czc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:hexagon-close-duocolor-round" {...props}></Icon>
<style>
:global(.m5m2x9czc) {
  d: path("M20 12v3c0 1.226-.774 2.387-2 3l-4 2a4.47 4.47 0 0 1-4 0l-4-2c-1.226-.613-2-1.774-2-3V9c0-1.226.774-2.387 2-3l4-2a4.47 4.47 0 0 1 4 0l4 2c1.226.613 2 1.774 2 3z");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.tocao8blo) {
  stroke-opacity: 0.4;
  d: path("m10 10l4 4m0-4l-4 4");
}

</style>
