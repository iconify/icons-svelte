<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="c07le3bhf"/><path class="r1p5_ebae"/><path class="eh---ab1x"/><path class="ufny_ofux"/><path class="ldodvk1_f"/><path class="d6cu3qpew"/><path class="icp673bbo"/><path class="y1lnycw3l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:block-alert-duotone-thin" {...props}></Icon>
<style>
:global(.c07le3bhf) {
  fill: currentColor;
  d: path("M11 15a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.d6cu3qpew) {
  d: path("M17 3h4v18h-4");
}

:global(.eh---ab1x) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M17 3h4v18h-4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.icp673bbo) {
  d: path("M12 9v3");
}

:global(.ldodvk1_f) {
  d: path("M7 3H3v18h4");
}

:global(.r1p5_ebae) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M7 3H3v18h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ufny_ofux) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 9v3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.y1lnycw3l) {
  d: path("M11 15a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

</style>
