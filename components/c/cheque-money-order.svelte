<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="wrcg6qhaf"/><path class="bx-oiietc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:cheque-money-order" {...props}></Icon>
<style>
:global(.bx-oiietc) {
  d: path("M14 7h4.5v5.5H14ZM8.5 8.25c1-.75 1.75.75 2.75 0M5.5 9h5m-5 4H9m3.5 3h6");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.wrcg6qhaf) {
  d: path("M2.5 4.5h19v15h-19Z");
}

</style>
