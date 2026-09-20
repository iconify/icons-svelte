<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vxdgzqbaj"/><path class="dktry7bqc"/><path class="lehy25blz"/><path class="x97k8ra4p"/><path class="d-6t8wivu"/><path class="t1sjjacis"/><path class="v9x83kt1r"/><path class="bo51iypxr"/><path class="icwp0hwav"/><path class="epoh96bbt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:chain-of-thought-duotone-thin" {...props}></Icon>
<style>
:global(.bo51iypxr) {
  d: path("M10 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.d-6t8wivu) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m13.5 13.5 3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.dktry7bqc) {
  fill: currentColor;
  d: path("M10 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.epoh96bbt) {
  d: path("M16 18a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.icwp0hwav) {
  d: path("m13.5 13.5 3 3");
}

:global(.lehy25blz) {
  fill: currentColor;
  d: path("M16 18a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.t1sjjacis) {
  d: path("M4 6a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.v9x83kt1r) {
  d: path("m7.5 7.5 3 3");
}

:global(.vxdgzqbaj) {
  fill: currentColor;
  d: path("M4 6a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.x97k8ra4p) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m7.5 7.5 3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
