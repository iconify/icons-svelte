<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lu8t8bbdh"/><path class="ior14cbcm"/><path class="an3s26btu"/><path class="eh0jdl8_z"/><path class="k187sabpz"/><path class="z9ittvbis"/><path class="mia87q3wc"/><path class="a1mgubcgh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:pantry-duotone-thin" {...props}></Icon>
<style>
:global(.a1mgubcgh) {
  d: path("M13 19v-5h4v5");
}

:global(.an3s26btu) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M5 11V6h4v5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.eh0jdl8_z) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M13 19v-5h4v5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ior14cbcm) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 19h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.k187sabpz) {
  d: path("M2 11h20");
}

:global(.lu8t8bbdh) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 11h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.mia87q3wc) {
  d: path("M5 11V6h4v5");
}

:global(.z9ittvbis) {
  d: path("M2 19h20");
}

</style>
