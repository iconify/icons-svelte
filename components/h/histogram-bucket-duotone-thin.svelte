<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qioqopbzb"/><path class="gms_xv68n"/><path class="yu-j7jb_g"/><path class="ujqhexc6h"/><path class="zcnr_ub9e"/><path class="u4-r-vgqa"/><path class="r3faxubne"/><path class="oifr9zbpt"/><path class="i-xxtdbfm"/><path class="b8iynqbad"/><path class="h4nnknbvo"/><path class="zw6iqebrn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:histogram-bucket-duotone-thin" {...props}></Icon>
<style>
:global(.b8iynqbad) {
  d: path("M13 8v10");
}

:global(.gms_xv68n) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.h4nnknbvo) {
  d: path("M17 13v5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.i-xxtdbfm) {
  d: path("M9 11v7");
}

:global(.oifr9zbpt) {
  d: path("M4 20h16");
}

:global(.qioqopbzb) {
  fill: currentColor;
  d: path("M12 5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.r3faxubne) {
  d: path("M4 4v16");
}

:global(.u4-r-vgqa) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M17 13v5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ujqhexc6h) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M9 11v7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.yu-j7jb_g) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 20h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.zcnr_ub9e) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M13 8v10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.zw6iqebrn) {
  d: path("M12 5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

</style>
