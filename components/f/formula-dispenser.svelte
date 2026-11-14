<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="rve-ifblg"/><path class="yyq6y1b0t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:formula-dispenser" {...props}></Icon>
<style>
:global(.rve-ifblg) {
  d: path("M6 9h12v12.5H6ZM5 6h14v3H5Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.yyq6y1b0t) {
  d: path("m6.5 3.5l6.5-1h5c0 4.75-5 4.75-5 0");
}

</style>
