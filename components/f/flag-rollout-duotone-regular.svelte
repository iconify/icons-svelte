<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="qlvopac9f"/><path class="qnvjj7b8l"/><path class="cr07o_obe"/><path class="v5wtc4_tk"/><path class="bb8zwb9ye"/><path class="crv4i00bu"/><path class="lulmb9b1a"/><path class="kow2ilbqy"/><path class="zos4srk3e"/><path class="y40ry_bij"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:flag-rollout-duotone-regular" {...props}></Icon>
<style>
:global(.bb8zwb9ye) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M14 6v7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.cr07o_obe) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M8 10v3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.crv4i00bu) {
  d: path("M4 3v18");
}

:global(.kow2ilbqy) {
  d: path("M8 10v3");
}

:global(.lulmb9b1a) {
  d: path("M4 4h16v12H4");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.qlvopac9f) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 3v18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.qnvjj7b8l) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 4h16v12H4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.v5wtc4_tk) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M11 8v5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.y40ry_bij) {
  d: path("M14 6v7");
}

:global(.zos4srk3e) {
  d: path("M11 8v5");
}

</style>
