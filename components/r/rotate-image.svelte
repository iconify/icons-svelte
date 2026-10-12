<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="wabgcc_pk"/><path class="k5wsglbre"/><path class="ccrg9bb5j"/><path class="krrr2ufus"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:rotate-image" {...props}></Icon>
<style>
:global(.ccrg9bb5j) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m6.75 21.25l3.75-3.75a1.4 1.4 0 0 1 2 0l1.75 1.75m-2-15.5H13a6 6 0 0 1 6 6v2");
}

:global(.k5wsglbre) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6.5 13.5h.01");
}

:global(.krrr2ufus) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M16.75 9.5L19 11.75l2.25-2.25");
}

:global(.wabgcc_pk) {
  width: 11.5px;
  height: 11.5px;
  x: 2.75px;
  y: 9.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2px;
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
