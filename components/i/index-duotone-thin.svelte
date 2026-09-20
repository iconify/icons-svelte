<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gms_xv68n"/><path class="s4g6c2bbl"/><path class="rls-tsgvm"/><path class="i1wzz86py"/><path class="r3faxubne"/><path class="rxxtm7qkj"/><path class="einbtqqgb"/><path class="mldnorr-p"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:index-duotone-thin" {...props}></Icon>
<style>
:global(.einbtqqgb) {
  d: path("M7 12h13");
}

:global(.gms_xv68n) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.i1wzz86py) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M7 17h13");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.mldnorr-p) {
  d: path("M7 17h13");
}

:global(.r3faxubne) {
  d: path("M4 4v16");
}

:global(.rls-tsgvm) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M7 12h13");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.rxxtm7qkj) {
  d: path("M7 7h13");
}

:global(.s4g6c2bbl) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M7 7h13");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
