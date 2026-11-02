<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="dd3c4cc7r"/><path class="r1g6yn7hp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:armchair-duocolor-sharp" {...props}></Icon>
<style>
:global(.dd3c4cc7r) {
  stroke-opacity: 0.4;
  d: path("M6 9V4h12v5");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.r1g6yn7hp) {
  d: path("M4 11v7h16v-7a2 2 0 1 0-4 0v2H8v-2a2 2 0 1 0-4 0m2 7v2m12-2v2");
}

</style>
