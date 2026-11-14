<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="esbah1bxw"/><path class="aky31soxm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:pos-item-lookup" {...props}></Icon>
<style>
:global(.aky31soxm) {
  d: path("m3 7l9 4.5L21 7m-9 4.5v4m0 3.5v2.5M7.5 4.75l9 4.5m-2 8a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0Zm4.75 2l2.25 2.25");
}

:global(.esbah1bxw) {
  d: path("M13.095 20.952L12 21.5L3 17V7l9-4.5L21 7v6.138");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
