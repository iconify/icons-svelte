<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="hl_mejm0r"/><path class="i8aq9_b_u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:arrow-up-to-line-duocolor-round" {...props}></Icon>
<style>
:global(.hl_mejm0r) {
  stroke-opacity: 0.4;
  d: path("M6 4h12");
}

:global(.i8aq9_b_u) {
  d: path("m16 12l-4-4l-4 4m4-4v12");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
