<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vpuel0dtu"/><path class="bnrf8ghpe"/><path class="plyg_abbd"/><path class="z7xxbcivi"/><path class="crv4i00bu"/><path class="lulmb9b1a"/><path class="icvc39peu"/><path class="xios20bld"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:milestone-filter-duotone-thin" {...props}></Icon>
<style>
:global(.bnrf8ghpe) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 4h16v12H4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.crv4i00bu) {
  d: path("M4 3v18");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.icvc39peu) {
  d: path("m9 7 3 3 3 -3");
}

:global(.lulmb9b1a) {
  d: path("M4 4h16v12H4");
}

:global(.plyg_abbd) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m9 7 3 3 3 -3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.vpuel0dtu) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 3v18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.xios20bld) {
  d: path("M12 10v3");
}

:global(.z7xxbcivi) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 10v3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
