<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="i75codbru"/><path class="ug169qsnj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:ceiling-height" {...props}></Icon>
<style>
:global(.i75codbru) {
  d: path("M3 2.5h18v19H3Zm9 3v13");
}

:global(.ug169qsnj) {
  d: path("M9.5 8L12 5.5L14.5 8m-5 8l2.5 2.5l2.5-2.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
