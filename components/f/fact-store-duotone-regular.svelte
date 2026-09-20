<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="m8c8atiya"/><path class="pfjq2-b9j"/><path class="n0n63pb2v"/><path class="xn7bwccty"/><path class="sj2zz9b3r"/><path class="dy-bj6bwq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:fact-store-duotone-regular" {...props}></Icon>
<style>
:global(.dy-bj6bwq) {
  d: path("M14 10a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
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

:global(.pfjq2-b9j) {
  fill: currentColor;
  d: path("M14 10a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.sj2zz9b3r) {
  d: path("M8 10h4");
}

:global(.xn7bwccty) {
  d: path("M8 6h8");
}

</style>
