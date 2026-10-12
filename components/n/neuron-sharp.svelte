<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><circle class="gyt-x0byx"/><path class="oi19_iuvc"/><path class="ov4y9abnf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:neuron-sharp" {...props}></Icon>
<style>
:global(.gyt-x0byx) {
  cx: 8.75px;
  cy: 8.75px;
  r: 3.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.oi19_iuvc) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8.75 8.75h.01");
}

:global(.ov4y9abnf) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m5.75 5.75l-2-2m5 .75V2.75m-4.25 6H2.75m3 3l-2 2m8-8l2-2M12 12l5.75 5.75m0 0h3.5m-3.5 0v3.5");
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
