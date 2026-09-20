<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="fvrxg8amo"/><path class="ys1yigyvq"/><path class="c-wb1qndc"/><path class="sjbre6b6k"/><path class="im38brk4q"/><path class="o1865wbjz"/><path class="ia46_gbxj"/><path class="btgfappwg"/><path class="i-zd2i_hi"/><path class="uxyzhxvwz"/><path class="rz_vrfdnw"/><path class="f8arnkt8y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:ranking-duotone-regular" {...props}></Icon>
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

:global(.i-zd2i_hi) {
  d: path("M3 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.ia46_gbxj) {
  d: path("M3 6a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.im38brk4q) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M7 12h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.o1865wbjz) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M7 18h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.rz_vrfdnw) {
  d: path("M3 18a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.sjbre6b6k) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M7 6h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.uxyzhxvwz) {
  d: path("M7 12h10");
}

:global(.ys1yigyvq) {
  fill: currentColor;
  d: path("M3 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
