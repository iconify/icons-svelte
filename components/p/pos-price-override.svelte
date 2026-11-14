<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="rre4cbcgc"/><path class="kvk83nbzx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:pos-price-override" {...props}></Icon>
<style>
:global(.kvk83nbzx) {
  d: path("M13.75 17.75a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm4 0H22m-2 0V20m2-2.25v1.75");
}

:global(.rre4cbcgc) {
  d: path("M11.3 19.5H8.5l-5-7.5l5-7.5h11v10.3M8.25 12h.01");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
