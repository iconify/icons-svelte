<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="hn7tnnbwb"/><path class="o_y3pbzrg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:cheque-draft" {...props}></Icon>
<style>
:global(.hn7tnnbwb) {
  d: path("M2.5 5h19v14h-19Z");
}

:global(.o_y3pbzrg) {
  d: path("m5 9.5l2.5-1.75L10 9.5m-4 0V12m3-2.5V12m-4 0h5m3.75-4.25h5V11h-5ZM5.5 15.5h4m3 0h6.25");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
