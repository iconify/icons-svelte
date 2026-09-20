<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ibuanu9pl"/><path class="yde2vxf3y"/><path class="ek73ljbuo"/><path class="mtq0bpb9h"/><path class="bt_2bvgpa"/><path class="mqtixbwqo"/><path class="lzdsnnb7v"/><path class="m91y9qbhe"/><path class="gbxzirw0u"/><path class="rkhcgsbdl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:perspective-drawing-duotone-thin" {...props}></Icon>
<style>
:global(.bt_2bvgpa) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 19h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ek73ljbuo) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 19 13 9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.gbxzirw0u) {
  d: path("M21 19 11 9");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
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

:global(.mtq0bpb9h) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M21 19 11 9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.rkhcgsbdl) {
  d: path("M3 19h18");
}

:global(.yde2vxf3y) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 8h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
