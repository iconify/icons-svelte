<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="ibuanu9pl"/><path class="trirghiqk"/><path class="u402o9-bj"/><path class="nf1bw6o1k"/><path class="xaz90clio"/><path class="mqtixbwqo"/><path class="lzdsnnb7v"/><path class="m91y9qbhe"/><path class="gbxzirw0u"/><path class="rkhcgsbdl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:perspective-drawing-duotone-bold" {...props}></Icon>
<style>
:global(.gbxzirw0u) {
  d: path("M21 19 11 9");
}

:global(.ibuanu9pl) {
  fill: currentColor;
  d: path("M11 8a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.lzdsnnb7v) {
  d: path("M11 8a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.m91y9qbhe) {
  d: path("M3 19 13 9");
}

:global(.mqtixbwqo) {
  d: path("M2 8h20");
}

:global(.nf1bw6o1k) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M21 19 11 9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.rkhcgsbdl) {
  d: path("M3 19h18");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.trirghiqk) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 8h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.u402o9-bj) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 19 13 9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.xaz90clio) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 19h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
