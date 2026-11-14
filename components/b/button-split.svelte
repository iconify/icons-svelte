<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="htuf028kj"/><path class="p47ibdq9c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:button-split" {...props}></Icon>
<style>
:global(.htuf028kj) {
  d: path("M2.5 6h19v12h-19Zm11 0v12M6 12h4.5");
}

:global(.p47ibdq9c) {
  d: path("m16 11l1.5 1.5L19 11");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
