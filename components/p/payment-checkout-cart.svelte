<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="od2uvqb2v"/><path class="yt2ytpejg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:payment-checkout-cart" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.od2uvqb2v) {
  d: path("M7.887 7h10.431a1.75 1.75 0 0 1 1.709 2.13l-.222 1a1.75 1.75 0 0 1-1.709 1.37H8.981a1.75 1.75 0 0 1-1.493-.837L6.625 9.25A1.479 1.479 0 0 1 7.887 7");
}

:global(.yt2ytpejg) {
  d: path("M2.5 3.5h2L7 15h8m-8 4a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m6.5 0a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0");
}

</style>
