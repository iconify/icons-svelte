<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="k_2z93bzc"/><path class="iwtuffbda"/><path class="ukvbw5baa"/><path class="uklz8h1xv"/><path class="gc_7z68hj"/><path class="ce9iv3bun"/><path class="rw2cw9fuy"/><path class="ks612kq_w"/><path class="mnv4pvbmf"/><path class="n3p0zmbop"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:bitemporal-duotone-thin" {...props}></Icon>
<style>
:global(.ce9iv3bun) {
  d: path("M4 3v17");
}

:global(.gc_7z68hj) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m12 12 6 -6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.iwtuffbda) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 3v17");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.k_2z93bzc) {
  fill: currentColor;
  d: path("M11 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.ks612kq_w) {
  d: path("m7 17 5 -5");
}

:global(.mnv4pvbmf) {
  d: path("m12 12 6 -6");
}

:global(.n3p0zmbop) {
  d: path("M11 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.rw2cw9fuy) {
  d: path("M4 20h17");
}

:global(.uklz8h1xv) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m7 17 5 -5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ukvbw5baa) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 20h17");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
