<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="u7krd6bbu"/><path class="h_n0_4bij"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:cart-wheelchair" {...props}></Icon>
<style>
:global(.h_n0_4bij) {
  d: path("M18 14v4.5h2.75l1 3M18 12.25h.01");
}

:global(.u7krd6bbu) {
  d: path("M2.5 2.5h2.25l2 9h8.43m.697-2.036L17.25 5h-12M8 14.5h.01m5.49 0h.01m.99 4.75a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
