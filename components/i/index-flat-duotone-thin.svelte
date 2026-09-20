<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="u2mvrstlq"/><path class="r7rhcrycy"/><path class="cllzgnvrr"/><path class="vfzgreb6n"/><path class="cj2tbzbzv"/><path class="y-vga5bbj"/><path class="uilxv67me"/><path class="isrkj8blm"/><path class="bvj__8b4y"/><path class="rrc90qj9p"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:index-flat-duotone-thin" {...props}></Icon>
<style>
:global(.bvj__8b4y) {
  d: path("M20 4v11");
}

:global(.cj2tbzbzv) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m18 13 2 2 2 -2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.cllzgnvrr) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 17h13");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.isrkj8blm) {
  d: path("M3 17h13");
}

:global(.r7rhcrycy) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 11h13");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.rrc90qj9p) {
  d: path("m18 13 2 2 2 -2");
}

:global(.u2mvrstlq) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 5h13");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.uilxv67me) {
  d: path("M3 11h13");
}

:global(.vfzgreb6n) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M20 4v11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.y-vga5bbj) {
  d: path("M3 5h13");
}

</style>
