<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="m8c8atiya"/><path class="n0n63pb2v"/><path class="xn7bwccty"/><path class="duvzkqbwy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:privacy-request-queue-duotone-regular" {...props}></Icon>
<style>
:global(.duvzkqbwy) {
  d: path("M8 9.5h8");
}

:global(.m8c8atiya) {
  fill: currentColor;
  d: path("M4 15v4h16v-4");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.n0n63pb2v) {
  d: path("M4 15v4h16v-4");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.xn7bwccty) {
  d: path("M8 6h8");
}

</style>
