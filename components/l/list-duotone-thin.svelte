<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fvrxg8amo"/><path class="ys1yigyvq"/><path class="c-wb1qndc"/><path class="sexqj6stx"/><path class="avz09zu-i"/><path class="ysz9fsfup"/><path class="ia46_gbxj"/><path class="p_zb4d-3a"/><path class="i-zd2i_hi"/><path class="bzecsub_a"/><path class="rz_vrfdnw"/><path class="k-_zk7bee"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:list-duotone-thin" {...props}></Icon>
<style>
:global(.avz09zu-i) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M8 12h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.bzecsub_a) {
  d: path("M8 12h12");
}

:global(.c-wb1qndc) {
  fill: currentColor;
  d: path("M3 18a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
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

:global(.i-zd2i_hi) {
  d: path("M3 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.ia46_gbxj) {
  d: path("M3 6a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.k-_zk7bee) {
  d: path("M8 18h12");
}

:global(.p_zb4d-3a) {
  d: path("M8 6h12");
}

:global(.rz_vrfdnw) {
  d: path("M3 18a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.sexqj6stx) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M8 6h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ys1yigyvq) {
  fill: currentColor;
  d: path("M3 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.ysz9fsfup) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M8 18h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
