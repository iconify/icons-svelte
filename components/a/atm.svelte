<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="wffwdccte"/><path class="g4y4k_cbg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:atm" {...props}></Icon>
<style>
:global(.g4y4k_cbg) {
  d: path("M7 5.5h10v6H7Zm.75 9h.01m2.74 0h.01m2.99 0h2.75m-8.75 4h9");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.wffwdccte) {
  d: path("M4 2.5h16v19H4Z");
}

</style>
