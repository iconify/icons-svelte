<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rpwh70njc"/><path class="jmtlq654c"/><path class="d52t8wbsd"/><path class="gbe32p-qb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:puddle-duotone-thin" {...props}></Icon>
<style>
:global(.d52t8wbsd) {
  d: path("m12 4 2.5 2.5a2.5 2.5 0 0 1 -5 0Z");
}

:global(.gbe32p-qb) {
  d: path("M3 15a9 3.5 0 1 0 18 0 9 3.5 0 1 0 -18 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jmtlq654c) {
  fill: currentColor;
  d: path("M3 15a9 3.5 0 1 0 18 0 9 3.5 0 1 0 -18 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.rpwh70njc) {
  fill: currentColor;
  d: path("m12 4 2.5 2.5a2.5 2.5 0 0 1 -5 0Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
