<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zhcvwjnws"/><path class="yqql_ccjj"/><path class="advi1_bna"/><path class="a-ud5-dfd"/><path class="gghvfjb1o"/><path class="h5sglqb0f"/><path class="h3z56pbbf"/><path class="z_si_bbvo"/><path class="a51oytv8p"/><path class="pv_diebju"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:learning-path-duotone-thin" {...props}></Icon>
<style>
:global(.a-ud5-dfd) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m4 20 5 -5v-5l5 -5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.a51oytv8p) {
  d: path("M13 4a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.advi1_bna) {
  fill: currentColor;
  d: path("M13 4a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.gghvfjb1o) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M17 21h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.h3z56pbbf) {
  d: path("M2 20a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.h5sglqb0f) {
  d: path("m4 20 5 -5v-5l5 -5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.pv_diebju) {
  d: path("M17 21h4");
}

:global(.yqql_ccjj) {
  fill: currentColor;
  d: path("M8 12.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.z_si_bbvo) {
  d: path("M8 12.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.zhcvwjnws) {
  fill: currentColor;
  d: path("M2 20a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
