<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="vw1395tua"/><path class="lffd_v9wc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:hair-coloring" {...props}></Icon>
<style>
:global(.lffd_v9wc) {
  d: path("m9.677 5.891l3.182 3.182l-3.536 3.536l-3.182-3.182ZM11.25 7.5l5-5m-8.75 13h9");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.vw1395tua) {
  d: path("M3 12.5h18c0 5-4 8-9 8s-9-3-9-8Z");
}

</style>
