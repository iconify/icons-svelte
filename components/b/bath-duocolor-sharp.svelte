<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="npsmtdbwc"/><path class="oq9txocbr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:bath-duocolor-sharp" {...props}></Icon>
<style>
:global(.npsmtdbwc) {
  stroke-opacity: 0.4;
  d: path("M5 12V4h4v2");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.oq9txocbr) {
  d: path("M3 12h18M5 12v6h14v-6M8 18v2m8-2v2");
}

</style>
