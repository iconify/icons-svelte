<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="g1ztaob7y"/><path class="mifla9vvb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:bluetooth-sharp" {...props}></Icon>
<style>
:global(.g1ztaob7y) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m6.75 7.25l10.5 9.5l-5.25 4.5V2.75l5.25 4.5l-10.5 9.5");
}

:global(.mifla9vvb) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3.5 12h.01m16.99 0h.01");
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
