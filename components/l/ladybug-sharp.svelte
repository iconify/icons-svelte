<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><circle class="l1t3aso4n"/><path class="qra194bsw"/><path class="bwyrovbmj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:ladybug-sharp" {...props}></Icon>
<style>
:global(.bwyrovbmj) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8.75 11.75h.01m6.49 0h.01M8.75 16h.01m6.49 0h.01");
}

:global(.l1t3aso4n) {
  cx: 12px;
  cy: 13.75px;
  r: 7.5px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.qra194bsw) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.25 6.5a3.75 3.25 0 0 1 7.5 0ZM12 8v12");
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
