<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="twtu48bgy"/><path class="qwldjk9vz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:drone-duocolor-sharp" {...props}></Icon>
<style>
:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.qwldjk9vz) {
  d: path("M10 9h4v6h-4Zm0-4a3.605 3.605 0 1 0-5 5m14 0a3.605 3.605 0 1 0-5-5m0 14a3.605 3.605 0 1 0 5-5M5 14a3.605 3.605 0 1 0 5 5");
}

:global(.twtu48bgy) {
  stroke-opacity: 0.4;
  d: path("m7 7l3 3m7-3l-3 3m-7 7l3-3m7 3l-3-3");
}

</style>
