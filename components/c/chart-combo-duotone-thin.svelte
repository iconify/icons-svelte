<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="r3ry-mu7u"/><path class="pqhroie3c"/><path class="nxauq4bbi"/><path class="bt_2bvgpa"/><path class="t_hkgmbup"/><path class="pbz4y6llk"/><path class="xqz890wro"/><path class="ejtyvbbdg"/><path class="rkhcgsbdl"/><path class="t4vjq-bqk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:chart-combo-duotone-thin" {...props}></Icon>
<style>
:global(.bt_2bvgpa) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 19h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ejtyvbbdg) {
  d: path("M17 15v4");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.nxauq4bbi) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M17 15v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.pbz4y6llk) {
  d: path("M5 13v6");
}

:global(.pqhroie3c) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M11 12v7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.r3ry-mu7u) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M5 13v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.rkhcgsbdl) {
  d: path("M3 19h18");
}

:global(.t_hkgmbup) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m4 9 4 -4 4 4 4 -4 4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.t4vjq-bqk) {
  d: path("m4 9 4 -4 4 4 4 -4 4 4");
}

:global(.xqz890wro) {
  d: path("M11 12v7");
}

</style>
