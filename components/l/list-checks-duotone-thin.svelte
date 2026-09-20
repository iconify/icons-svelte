<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ccvs8vkcj"/><path class="mm6_dwsdt"/><path class="ozs1mubcb"/><path class="i7n1d_bbc"/><path class="j01wtf-ud"/><path class="b_0b3gy_e"/><path class="dm_ar8wjk"/><path class="z5u11lbdo"/><path class="z4f7qacqo"/><path class="g9c4ykb9u"/><path class="myi37dz6l"/><path class="syk7o8b5x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:list-checks-duotone-thin" {...props}></Icon>
<style>
:global(.b_0b3gy_e) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M11 17h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ccvs8vkcj) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m3 7 2 2 3 -3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.dm_ar8wjk) {
  d: path("m3 7 2 2 3 -3");
}

:global(.g9c4ykb9u) {
  d: path("M11 12h10");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.i7n1d_bbc) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M11 12h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.j01wtf-ud) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m3 17 2 2 3 -3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.mm6_dwsdt) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M11 7h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.myi37dz6l) {
  d: path("m3 17 2 2 3 -3");
}

:global(.ozs1mubcb) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m3 12 2 2 3 -3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.syk7o8b5x) {
  d: path("M11 17h10");
}

:global(.z4f7qacqo) {
  d: path("m3 12 2 2 3 -3");
}

:global(.z5u11lbdo) {
  d: path("M11 7h10");
}

</style>
