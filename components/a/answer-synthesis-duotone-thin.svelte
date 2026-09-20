<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="swquduh2r"/><path class="t8qt32blf"/><path class="cvqe-8bsy"/><path class="hiw2q-bac"/><path class="xl9i5ac4s"/><path class="z7e_phf6k"/><path class="b7nacdcee"/><path class="d223d_x9q"/><path class="d_scobift"/><path class="ymrjh3b_x"/><path class="k2jd848hu"/><path class="f2m4wubik"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:answer-synthesis-duotone-thin" {...props}></Icon>
<style>
:global(.b7nacdcee) {
  d: path("M3 6h6");
}

:global(.cvqe-8bsy) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 18h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.d_scobift) {
  d: path("M3 18h6");
}

:global(.d223d_x9q) {
  d: path("M3 12h6");
}

:global(.f2m4wubik) {
  d: path("M13 12h8");
}

:global(.hiw2q-bac) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m9 8 4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.k2jd848hu) {
  d: path("m9 16 4 -4");
}

:global(.swquduh2r) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 6h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.t8qt32blf) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 12h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.xl9i5ac4s) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m9 16 4 -4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ymrjh3b_x) {
  d: path("m9 8 4 4");
}

:global(.z7e_phf6k) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M13 12h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
