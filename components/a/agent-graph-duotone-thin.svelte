<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="t7scrr-5w"/><path class="p8iop6bwz"/><path class="lcuc7cckr"/><path class="eooj7zbvk"/><path class="khvc4wbcc"/><path class="z_rogeb3e"/><path class="gfyw8vbbf"/><path class="d-v-f28sf"/><path class="c-xj8zban"/><path class="q1jaj6b2n"/><path class="chx4f6b7j"/><path class="y69n27oio"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:agent-graph-duotone-thin" {...props}></Icon>
<style>
:global(.c-xj8zban) {
  d: path("M20 14a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.chx4f6b7j) {
  d: path("m14 15 2 2");
}

:global(.d-v-f28sf) {
  d: path("M12 14a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.eooj7zbvk) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M7.69 2.37a4 4 0 1 1 -3.38 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.gfyw8vbbf) {
  d: path("M7.69 2.37a4 4 0 1 1 -3.38 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.khvc4wbcc) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m14 15 2 2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.lcuc7cckr) {
  fill: currentColor;
  d: path("M16 18a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.p8iop6bwz) {
  fill: currentColor;
  d: path("M20 14a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.q1jaj6b2n) {
  d: path("M16 18a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.t7scrr-5w) {
  fill: currentColor;
  d: path("M12 14a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.y69n27oio) {
  d: path("m20 15 -2 2");
}

:global(.z_rogeb3e) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m20 15 -2 2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
