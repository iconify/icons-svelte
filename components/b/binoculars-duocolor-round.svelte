<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="cw239tpsx"/><path class="eq9yi4b5o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:binoculars-duocolor-round" {...props}></Icon>
<style>
:global(.cw239tpsx) {
  stroke-opacity: 0.4;
  d: path("M3 16c0-3 4-6 4-8V7a1 1 0 0 1 2 0v9m12 0c0-3-4-6-4-8V7a1 1 0 0 0-2 0v9");
}

:global(.eq9yi4b5o) {
  d: path("M3 16a3 3 0 1 0 6 0a3 3 0 0 0-6 0m12 0a3 3 0 1 0 6 0a3 3 0 0 0-6 0m-6-5h6");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
