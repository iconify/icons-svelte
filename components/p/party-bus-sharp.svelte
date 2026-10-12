<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="hwg6dtb6f"/><path class="n0uizqw5r"/><path class="eehfmvbwm"/><circle class="r_0b548wt"/><path class="ox2ue_b-w"/><circle class="hha4cxblz"/><path class="l0haxibzw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:party-bus-sharp" {...props}></Icon>
<style>
:global(.eehfmvbwm) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8 3h.01M16 3h.01");
}

:global(.hha4cxblz) {
  cx: 17px;
  cy: 19px;
  r: 2.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.hwg6dtb6f) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 6h18.5v10.75H2.75z");
}

:global(.l0haxibzw) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M17 19h.01");
}

:global(.n0uizqw5r) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.75 9h2.5v2.5h-2.5Zm5 0h2.5v2.5h-2.5Zm5 0h2.5v2.5h-2.5Z");
}

:global(.ox2ue_b-w) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 19h.01");
}

:global(.r_0b548wt) {
  cx: 7px;
  cy: 19px;
  r: 2.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
