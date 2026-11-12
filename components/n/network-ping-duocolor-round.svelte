<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="y-lpg7b8m"/><path class="sn1wpsbou"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:network-ping-duocolor-round" {...props}></Icon>
<style>
:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.sn1wpsbou) {
  d: path("M3 18a2 2 0 1 0 4 0a2 2 0 0 0-4 0M17 5a2 2 0 1 0 4 0a2 2 0 0 0-4 0");
}

:global(.y-lpg7b8m) {
  stroke-opacity: 0.4;
  d: path("M5 11c4 0 7 3 7 7M5 5c7 0 13 6 13 13");
}

</style>
