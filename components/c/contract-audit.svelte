<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="dhqtyub_i"/><path class="xuwa0cc1t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:contract-audit" {...props}></Icon>
<style>
:global(.dhqtyub_i) {
  d: path("M11.8 19H2.5V3h18v9.3");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.xuwa0cc1t) {
  d: path("M8.5 7L6 9.75l2.5 2.75m5-5.5L16 9.75l-2.5 2.75m1.25 5.5l2 2L21 15.75");
}

</style>
