<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="i9ysg0b3h"/><path class="d3_0351ap"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:one-way-sign" {...props}></Icon>
<style>
:global(.d3_0351ap) {
  d: path("m14.5 9l3 3l-3 3");
}

:global(.i9ysg0b3h) {
  d: path("M2 6h20v12H2Zm3.5 6h12");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
