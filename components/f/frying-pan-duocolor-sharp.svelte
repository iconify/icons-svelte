<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="rqyts8bos"/><path class="nedp8zb0g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:frying-pan-duocolor-sharp" {...props}></Icon>
<style>
:global(.nedp8zb0g) {
  d: path("M3 11h12v5H3z");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.rqyts8bos) {
  stroke-opacity: 0.4;
  d: path("m15 11l6-3");
}

</style>
