<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="lz692cbkn"/><path class="p8fnjac2o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:hexagon-minus-duocolor-sharp" {...props}></Icon>
<style>
:global(.lz692cbkn) {
  stroke-opacity: 0.4;
  d: path("M9 12h6");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.p8fnjac2o) {
  d: path("M20 12v5l-8 4l-8-4V7l8-4l8 4z");
}

</style>
