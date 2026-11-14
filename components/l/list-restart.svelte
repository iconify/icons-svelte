<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="g6zqrl81p"/><path class="w_q86u-ly"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:list-restart" {...props}></Icon>
<style>
:global(.g6zqrl81p) {
  d: path("M14.5 6h7m-7 7h7m-19 7h19M7 5.5A4.5 4.5 0 1 1 2.5 10");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.w_q86u-ly) {
  d: path("M4.75 3.25L7 5.5L4.75 7.75");
}

</style>
