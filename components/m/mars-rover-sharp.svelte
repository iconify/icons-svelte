<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="qe5pjcb6g"/><path class="hs3hiubkz"/><path class="f123brk0z"/><circle class="p6k37obuz"/><circle class="hs5razboj"/><circle class="hkf5sd0yi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:mars-rover-sharp" {...props}></Icon>
<style>
:global(.f123brk0z) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m5.5 16.5l3.5-3l3 3l3-3l3.5 3");
}

:global(.hkf5sd0yi) {
  cx: 18.5px;
  cy: 18.75px;
  r: 2.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.hs3hiubkz) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M16.75 4.25h.01");
}

:global(.hs5razboj) {
  cx: 12px;
  cy: 18.75px;
  r: 2.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.p6k37obuz) {
  cx: 5.5px;
  cy: 18.75px;
  r: 2.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.qe5pjcb6g) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 9.5h15v4h-15zm11 0V5.75M4.5 9.5L3 7.25m0 0h4.5m5.5-4.5h5.5v3H13z");
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
