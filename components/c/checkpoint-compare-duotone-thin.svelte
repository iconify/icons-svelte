<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vpuel0dtu"/><path class="q-ctreb7a"/><path class="gmcfcr4vz"/><path class="l1-pgfbtd"/><path class="crv4i00bu"/><path class="y-rdj5vjt"/><path class="tmdcbizpt"/><path class="l3l5pbb3j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:checkpoint-compare-duotone-thin" {...props}></Icon>
<style>
:global(.crv4i00bu) {
  d: path("M4 3v18");
}

:global(.gmcfcr4vz) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M14 3v18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.l1-pgfbtd) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M14 9h6.5v5H14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.l3l5pbb3j) {
  d: path("M14 9h6.5v5H14");
}

:global(.q-ctreb7a) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 5h6.5v5H4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.tmdcbizpt) {
  d: path("M14 3v18");
}

:global(.vpuel0dtu) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 3v18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.y-rdj5vjt) {
  d: path("M4 5h6.5v5H4");
}

</style>
