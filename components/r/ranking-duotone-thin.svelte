<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fvrxg8amo"/><path class="ys1yigyvq"/><path class="c-wb1qndc"/><path class="hxflp3w_w"/><path class="x7ap30bft"/><path class="wpwgiacak"/><path class="ia46_gbxj"/><path class="btgfappwg"/><path class="i-zd2i_hi"/><path class="uxyzhxvwz"/><path class="rz_vrfdnw"/><path class="f8arnkt8y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:ranking-duotone-thin" {...props}></Icon>
<style>
:global(.btgfappwg) {
  d: path("M7 6h14");
}

:global(.c-wb1qndc) {
  fill: currentColor;
  d: path("M3 18a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.f8arnkt8y) {
  d: path("M7 18h6");
}

:global(.fvrxg8amo) {
  fill: currentColor;
  d: path("M3 6a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
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

:global(.hxflp3w_w) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M7 6h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.i-zd2i_hi) {
  d: path("M3 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.ia46_gbxj) {
  d: path("M3 6a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.rz_vrfdnw) {
  d: path("M3 18a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.uxyzhxvwz) {
  d: path("M7 12h10");
}

:global(.wpwgiacak) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M7 18h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.x7ap30bft) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M7 12h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ys1yigyvq) {
  fill: currentColor;
  d: path("M3 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
