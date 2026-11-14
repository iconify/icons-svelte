<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="fr7ygbcyg"/><path class="htisrebay"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:bath-toys" {...props}></Icon>
<style>
:global(.fr7ygbcyg) {
  d: path("M5 13a3.75 3.75 0 1 1 6.75-2c1.25 2.5 4.75 2.5 8.25.5c.5 5-3 8.5-7.5 8.5c-5 0-7.5-3-7.5-7Z");
}

:global(.htisrebay) {
  d: path("m11.75 7.5l2.75.75l-2.75 1Zm-4 1h.01");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
