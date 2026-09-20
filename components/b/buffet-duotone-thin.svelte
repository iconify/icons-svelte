<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="f_hy4hbgg"/><path class="ydkgc70eo"/><path class="x9_hi749k"/><path class="qh0h9bdva"/><path class="qz3by1b6e"/><path class="zugrvnb7t"/><path class="e325robmt"/><path class="bfcwd7bcm"/><path class="v7ifz5bvw"/><path class="leijmjbkg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:buffet-duotone-thin" {...props}></Icon>
<style>
:global(.bfcwd7bcm) {
  d: path("M13 13a4 4 0 0 1 8 0");
}

:global(.e325robmt) {
  d: path("M3 13a4 4 0 0 1 8 0");
}

:global(.f_hy4hbgg) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 13h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.leijmjbkg) {
  d: path("M18 13v6");
}

:global(.qh0h9bdva) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 13v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.qz3by1b6e) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M18 13v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.v7ifz5bvw) {
  d: path("M6 13v6");
}

:global(.x9_hi749k) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M13 13a4 4 0 0 1 8 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ydkgc70eo) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 13a4 4 0 0 1 8 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.zugrvnb7t) {
  d: path("M2 13h20");
}

</style>
