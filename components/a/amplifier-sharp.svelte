<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="o3q106bmt"/><path class="zl5bs9bqu"/><circle class="ttf32rblh"/><circle class="mwwbpgbvl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:amplifier-sharp" {...props}></Icon>
<style>
:global(.mwwbpgbvl) {
  cx: 12px;
  cy: 14px;
  r: 1.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.o3q106bmt) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 2.75h14.5v18.5H4.75zm0 4.25h14.5");
}

:global(.ttf32rblh) {
  cx: 12px;
  cy: 14px;
  r: 4px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

:global(.zl5bs9bqu) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9.5 4.9h.01m2.49 0h.01m2.49 0h.01");
}

</style>
