<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="aa0k9nbrp"/><circle class="m6jsykbla"/><path class="bq7hn8bxr"/><path class="jg3mm4bct"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:cash-off-sharp" {...props}></Icon>
<style>
:global(.aa0k9nbrp) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 4.75h18.5v11.5H2.75z");
}

:global(.bq7hn8bxr) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5.75 10.5h.01m12.49 0h.01");
}

:global(.jg3mm4bct) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.25 19.25h13.5");
}

:global(.m6jsykbla) {
  cx: 12px;
  cy: 10.5px;
  r: 2.5px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
