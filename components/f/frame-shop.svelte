<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ccgro45ii"/><path class="hey4kh-pk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:frame-shop" {...props}></Icon>
<style>
:global(.ccgro45ii) {
  d: path("M3 7.5h18V21H3Z");
}

:global(.hey4kh-pk) {
  d: path("m6.5 18l4-5l3 3.5l1.75-1.75l2.25 2.5m-1.5-6h.01M7.5 7.5L12 3l4.5 4.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
