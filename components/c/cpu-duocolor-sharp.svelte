<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="fqdyy9brp"/><path class="j-yyzwbrc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:cpu-duocolor-sharp" {...props}></Icon>
<style>
:global(.fqdyy9brp) {
  stroke-opacity: 0.4;
  d: path("M10 10h4v4h-4Z");
}

:global(.j-yyzwbrc) {
  d: path("M6 6h12v12H6Zm4-3v3m0 12v3M3 10h3m12 0h3m-7-7v3m0 12v3M3 14h3m12 0h3");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
