<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="rkx2kcbka"/><path class="d3xxo4y6s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:drop-shadow-duocolor-sharp" {...props}></Icon>
<style>
:global(.d3xxo4y6s) {
  d: path("M3 3h12v12H3Z");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.rkx2kcbka) {
  stroke-opacity: 0.4;
  d: path("M7 21h14V7");
}

</style>
