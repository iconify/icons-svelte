<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="mie9b5bhx"/><path class="sg_8t8v0c"/><path class="xuv-p6wvo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:marketing-automation" {...props}></Icon>
<style>
:global(.mie9b5bhx) {
  d: path("M4.206 7.5a9 9 0 1 1 0 9");
}

:global(.sg_8t8v0c) {
  d: path("m4.5 3.5l3 .75L6.75 7M7 8.5h10v7H7Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.xuv-p6wvo) {
  d: path("M7.25 9.25L12 12.5l4.75-3.25");
}

</style>
