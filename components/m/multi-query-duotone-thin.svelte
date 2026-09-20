<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dba5rjonf"/><path class="zl5hlnbpt"/><path class="mrmp0wbtu"/><path class="un54rzefh"/><path class="lonp9bb5q"/><path class="ffw_pwyfz"/><path class="kfdmhd64i"/><path class="gjllsvbkd"/><path class="g-zzhsbrv"/><path class="r_4k1sbsg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:multi-query-duotone-thin" {...props}></Icon>
<style>
:global(.dba5rjonf) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12.62 3.5a7 7 0 1 1 -5.24 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ffw_pwyfz) {
  d: path("M12.62 3.5a7 7 0 1 1 -5.24 0");
}

:global(.g-zzhsbrv) {
  d: path("M7 10h6");
}

:global(.gjllsvbkd) {
  d: path("M7 7h6");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.kfdmhd64i) {
  d: path("m15 15 6 6");
}

:global(.lonp9bb5q) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M7 13h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.mrmp0wbtu) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M7 7h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.r_4k1sbsg) {
  d: path("M7 13h6");
}

:global(.un54rzefh) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M7 10h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.zl5hlnbpt) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m15 15 6 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
