<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="wn9f0oder"/><path class="h7-qtfayk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:ear-duocolor" {...props}></Icon>
<style>
:global(.h7-qtfayk) {
  d: path("M6 9a6 6 0 1 1 12 0c0 6-6 5-6 9a3 3 0 0 1-6 0");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.wn9f0oder) {
  stroke-opacity: 0.4;
  d: path("M14 9a2 2 0 1 0-4 0c2 0 2 3 0 3");
}

</style>
