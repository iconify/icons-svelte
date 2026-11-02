<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ss58g-prf"/><path class="oqdxdpjwb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:percent-duocolor-round" {...props}></Icon>
<style>
:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.oqdxdpjwb) {
  d: path("M19 5L5 19");
}

:global(.ss58g-prf) {
  stroke-opacity: 0.4;
  d: path("M5 7a2 2 0 1 0 4 0a2 2 0 0 0-4 0m10 10a2 2 0 1 0 4 0a2 2 0 0 0-4 0");
}

</style>
