<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="qi4j1fbqc"/><path class="d_ky6ccvq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:calcite-crystal" {...props}></Icon>
<style>
:global(.d_ky6ccvq) {
  d: path("M8 8h8l5-3m-5 3l-4 11");
}

:global(.qi4j1fbqc) {
  d: path("M4 19h8l5-3l4-11h-8L8 8Zm-1.5 0h19");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
