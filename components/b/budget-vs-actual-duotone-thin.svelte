<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hsnj9o-9y"/><path class="a9p3o_b1a"/><path class="t0tr_kbnd"/><path class="kdeocz3_k"/><path class="jkuojibnm"/><path class="nn2mbucfp"/><path class="wwyi7ubez"/><path class="om9c7ck0x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:budget-vs-actual-duotone-thin" {...props}></Icon>
<style>
:global(.a9p3o_b1a) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M5 20V8h5v12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.hsnj9o-9y) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 20h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.jkuojibnm) {
  d: path("M3 20h18");
}

:global(.kdeocz3_k) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M13 8h7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nn2mbucfp) {
  d: path("M5 20V8h5v12");
}

:global(.om9c7ck0x) {
  d: path("M13 8h7");
}

:global(.t0tr_kbnd) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M14 20v-6h5v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.wwyi7ubez) {
  d: path("M14 20v-6h5v6");
}

</style>
