<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="e5kwf6bjt"/><path class="ectmw1bny"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:brackets-dots-duocolor-round" {...props}></Icon>
<style>
:global(.e5kwf6bjt) {
  stroke-opacity: 0.4;
  d: path("M9 6h.01M15 6h.01M9 12h.01M15 12h.01M9 18h.01M15 18h.01");
}

:global(.ectmw1bny) {
  d: path("M6 3H5a2 2 0 0 0-2 2v14a2 2 0 0 0 2 2h1M18 3h1a2 2 0 0 1 2 2v14a2 2 0 0 1-2 2h-1");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
