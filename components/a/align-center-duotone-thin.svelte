<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="earhjk-cy"/><path class="gl3_cfeeg"/><path class="la945tbvd"/><path class="xgrfb-bqu"/><path class="qt4afwy9g"/><path class="ite_ehtoh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:align-center-duotone-thin" {...props}></Icon>
<style>
:global(.earhjk-cy) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 6h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.gl3_cfeeg) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6.5 12h11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ite_ehtoh) {
  d: path("M4.5 18h15");
}

:global(.la945tbvd) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4.5 18h15");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.qt4afwy9g) {
  d: path("M6.5 12h11");
}

:global(.xgrfb-bqu) {
  d: path("M3 6h18");
}

</style>
