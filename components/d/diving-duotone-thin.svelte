<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gl2wyfu4j"/><path class="pg8robb9a"/><path class="z449eibvb"/><path class="rw2clob2u"/><path class="b-zvzmq4t"/><path class="qj_kcbc2q"/><path class="q686vz2zk"/><path class="intk4nbhb"/><path class="g1wm5cc6f"/><path class="d147n4bfy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:diving-duotone-thin" {...props}></Icon>
<style>
:global(.b-zvzmq4t) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 20c3 -2 6 2 9 0s6 2 9 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.d147n4bfy) {
  d: path("M3 20c3 -2 6 2 9 0s6 2 9 0");
}

:global(.g1wm5cc6f) {
  d: path("m16 15 -3 3");
}

:global(.gl2wyfu4j) {
  fill: currentColor;
  d: path("M14 8a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.intk4nbhb) {
  d: path("M16 10v5");
}

:global(.pg8robb9a) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 6h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.q686vz2zk) {
  d: path("M14 8a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.qj_kcbc2q) {
  d: path("M3 6h10");
}

:global(.rw2clob2u) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m16 15 -3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.z449eibvb) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M16 10v5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
