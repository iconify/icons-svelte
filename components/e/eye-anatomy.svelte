<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="wdp7bqefo"/><path class="yeawnjmjy"/><path class="i13_tbbbr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:eye-anatomy" {...props}></Icon>
<style>
:global(.i13_tbbbr) {
  d: path("M19.5 12c.75.25 1.5 1 2 2.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.wdp7bqefo) {
  d: path("M4.5 12a7.5 7.5 0 1 0 15 0a7.5 7.5 0 1 0-15 0Z");
}

:global(.yeawnjmjy) {
  fill: currentColor;
  d: path("M4.5 8c1.5 1 2 2.5 2 4s-.5 3-2 4c-.75-1-1.25-2.5-1.25-4s.5-3 1.25-4Z");
}

</style>
