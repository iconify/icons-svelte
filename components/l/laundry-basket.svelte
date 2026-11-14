<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="g7ug3qq5h"/><path class="wpl78zkdi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:laundry-basket" {...props}></Icon>
<style>
:global(.g7ug3qq5h) {
  d: path("M3 10h18l-2 10.5H5Zm1 5.25h16M7.5 10V6.5l2.5-2h4l2.5 2V10");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.wpl78zkdi) {
  d: path("m10 4.5l2 2l2-2");
}

</style>
