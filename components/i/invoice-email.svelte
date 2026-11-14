<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="u7jpip1dv"/><path class="qo-c9xb-x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:invoice-email" {...props}></Icon>
<style>
:global(.qo-c9xb-x) {
  d: path("m3 11l9 5.5l9-5.5M9.5 6.5H14");
}

:global(.u7jpip1dv) {
  d: path("M2.5 10h19v11.5h-19Zm4 0V3.5l1.75-1l1.75 1l1.75-1l1.75 1l1.75-1l1.75 1V10");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
