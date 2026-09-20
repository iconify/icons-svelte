<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="c8h3t-z9z"/><path class="y80g12bwz"/><path class="jbmfbdcwk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:dairy-free-outline-regular" {...props}></Icon>
<style>
:global(.c8h3t-z9z) {
  d: path("M7 9v11h9V9Z");
}

:global(.jbmfbdcwk) {
  d: path("M4 21 20 5");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.y80g12bwz) {
  d: path("m7 9 4.5 -4.5L16 9");
}

</style>
