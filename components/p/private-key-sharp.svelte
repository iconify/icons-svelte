<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><circle class="o6y4byb0b"/><path class="q_nfnc6mi"/><path class="qbqaq4n_g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:private-key-sharp" {...props}></Icon>
<style>
:global(.o6y4byb0b) {
  cx: 7px;
  cy: 15px;
  r: 4.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.q_nfnc6mi) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 15h.01");
}

:global(.qbqaq4n_g) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.25 15h10M19 15v3m-2.75-3v2.25M14 5.75h7.25v5.75H14zm1.75 0V3h3.5v2.75");
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
