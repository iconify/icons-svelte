<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vxdgzqbaj"/><path class="lehy25blz"/><path class="x6c-ahbbn"/><path class="orqckmbqk"/><path class="hjd_aobvq"/><path class="ttnd6t8gp"/><path class="t1sjjacis"/><path class="epoh96bbt"/><path class="u5a77nl7p"/><path class="x_46rtfdb"/><path class="l576i2b9k"/><path class="y7za30bps"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:git-compare-duotone-thin" {...props}></Icon>
<style>
:global(.epoh96bbt) {
  d: path("M16 18a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.hjd_aobvq) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M18 15.5V10h-5.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.l576i2b9k) {
  d: path("M18 15.5V10h-5.5");
}

:global(.lehy25blz) {
  fill: currentColor;
  d: path("M16 18a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.orqckmbqk) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m9.5 12 2 2 -2 2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.t1sjjacis) {
  d: path("M4 6a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.ttnd6t8gp) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m14.5 8 -2 2 2 2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.u5a77nl7p) {
  d: path("M6 8.5V14h5.5");
}

:global(.vxdgzqbaj) {
  fill: currentColor;
  d: path("M4 6a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.x_46rtfdb) {
  d: path("m9.5 12 2 2 -2 2");
}

:global(.x6c-ahbbn) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 8.5V14h5.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.y7za30bps) {
  d: path("m14.5 8 -2 2 2 2");
}

</style>
