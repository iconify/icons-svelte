<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jz9jnbbik"/><path class="y36t9bcby"/><path class="ze6_11znx"/><path class="psjbxfbel"/><path class="u67l7tf7g"/><path class="aeyekmbly"/><path class="axr3xwb0d"/><path class="yk3ngthye"/><path class="dx_oex_yx"/><path class="umr6jbb1c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:provenance-duotone-thin" {...props}></Icon>
<style>
:global(.aeyekmbly) {
  d: path("M3 19a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.axr3xwb0d) {
  d: path("m7 17 4 -4");
}

:global(.dx_oex_yx) {
  d: path("m15 9 4 -4");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jz9jnbbik) {
  fill: currentColor;
  d: path("M3 19a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.psjbxfbel) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m7 17 4 -4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.u67l7tf7g) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m15 9 4 -4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.umr6jbb1c) {
  d: path("M18 5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.y36t9bcby) {
  fill: currentColor;
  d: path("M11 11a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.yk3ngthye) {
  d: path("M11 11a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.ze6_11znx) {
  fill: currentColor;
  d: path("M18 5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
