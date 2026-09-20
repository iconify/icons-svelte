<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xtqbfpzcr"/><path class="ior14cbcm"/><path class="euvekjzkt"/><path class="zmdi3vj7x"/><path class="k15q4tbdt"/><path class="z9ittvbis"/><path class="bnhdslb0j"/><path class="kyf663bil"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:dusk-duotone-thin" {...props}></Icon>
<style>
:global(.bnhdslb0j) {
  d: path("M19 8v6");
}

:global(.euvekjzkt) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M19 8v6");
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

:global(.k15q4tbdt) {
  d: path("M6 19a6 6 0 0 1 12 0");
}

:global(.kyf663bil) {
  d: path("M16.5 11.5 19 14l2.5 -2.5");
}

:global(.xtqbfpzcr) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 19a6 6 0 0 1 12 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.z9ittvbis) {
  d: path("M2 19h20");
}

:global(.zmdi3vj7x) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M16.5 11.5 19 14l2.5 -2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
