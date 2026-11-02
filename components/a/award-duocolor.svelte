<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="y6m2k97ce"/><path class="wxe2_ouwj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:award-duocolor" {...props}></Icon>
<style>
:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.wxe2_ouwj) {
  d: path("M6 9a6 6 0 1 0 12 0A6 6 0 0 0 6 9");
}

:global(.y6m2k97ce) {
  stroke-opacity: 0.4;
  d: path("m14 15l2 6l-4-2l-4 2l2-6");
}

</style>
