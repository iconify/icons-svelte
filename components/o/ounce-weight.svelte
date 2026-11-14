<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="nnkp-hh0e"/><path class="cdobhebmh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:ounce-weight" {...props}></Icon>
<style>
:global(.cdobhebmh) {
  d: path("m6.5 15l2-6h7l2 6Z");
}

:global(.nnkp-hh0e) {
  d: path("M2.5 18L6 6h12l3.5 12Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
