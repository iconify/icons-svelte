<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xqimmi-kt"/><path class="batj7bb2k"/><path class="nzvp0dheg"/><path class="sb4nxhxer"/><path class="qcf-nj9zp"/><path class="ljo-5rbrq"/><path class="f1psbbcsw"/><path class="kdl_ri28b"/><path class="lkivjibuo"/><path class="yzvng5w1c"/><path class="e-0451fwt"/><path class="c7dgfu7wx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:percentile-duotone-thin" {...props}></Icon>
<style>
:global(.batj7bb2k) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M8 11v9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.c7dgfu7wx) {
  d: path("M2 4h20");
}

:global(.e-0451fwt) {
  d: path("M20 16v4");
}

:global(.f1psbbcsw) {
  d: path("M4 15v5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.kdl_ri28b) {
  d: path("M8 11v9");
}

:global(.ljo-5rbrq) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 4h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.lkivjibuo) {
  d: path("M12 13v7");
}

:global(.nzvp0dheg) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 13v7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.qcf-nj9zp) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M20 16v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.sb4nxhxer) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M16 7v13");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.xqimmi-kt) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 15v5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.yzvng5w1c) {
  d: path("M16 7v13");
}

</style>
