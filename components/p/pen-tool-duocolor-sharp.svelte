<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="og3vf3u0p"/><path class="wbl-5ymyb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:pen-tool-duocolor-sharp" {...props}></Icon>
<style>
:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.og3vf3u0p) {
  stroke-opacity: 0.4;
  d: path("m4 4l4 4m3 3h.01");
}

:global(.wbl-5ymyb) {
  d: path("m4 4l10 3l3 6l-4 4l-6-3Zm13 9l3 3l-4 4l-3-3");
}

</style>
