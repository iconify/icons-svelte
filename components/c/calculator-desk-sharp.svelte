<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="rbostdcxq"/><path class="f7neuybxg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:calculator-desk-sharp" {...props}></Icon>
<style>
:global(.f7neuybxg) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 12h.01M15 12h.01M9 17h.01M15 17h.01");
}

:global(.rbostdcxq) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 2.75h14v18.5H5zM8 6.5h8");
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
