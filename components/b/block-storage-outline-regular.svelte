<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="oto6z4zwr"/><path class="nldbk4b3i"/><path class="l0v-b4kbr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:block-storage-outline-regular" {...props}></Icon>
<style>
:global(.l0v-b4kbr) {
  d: path("M8 12h8");
}

:global(.nldbk4b3i) {
  d: path("M4 6a8 3 0 0 0 16 0");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.oto6z4zwr) {
  d: path("M4 6a8 3 0 0 1 16 0v12a8 3 0 0 1 -16 0Z");
}

</style>
