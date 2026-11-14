<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="rylwk1z8m"/><path class="h_0vejb0e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:drop-ship-order" {...props}></Icon>
<style>
:global(.h_0vejb0e) {
  d: path("m12 15.5l4.75-4.75l4.75 4.75v6H12Z");
}

:global(.rylwk1z8m) {
  d: path("M2.5 2.5h6v6h-6Zm6 6l5.25 5.25m-3 0h3v-3");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
