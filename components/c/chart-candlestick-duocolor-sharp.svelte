<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="fbes49b5d"/><path class="gaewm6b7o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:chart-candlestick-duocolor-sharp" {...props}></Icon>
<style>
:global(.fbes49b5d) {
  stroke-opacity: 0.4;
  d: path("M5 12v3m0 5v1m7-18v2m0 7v3m7-3v3m0 4v2");
}

:global(.gaewm6b7o) {
  d: path("M3 15h4v5H3Zm7-10h4v7h-4Zm7 10h4v4h-4Z");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
