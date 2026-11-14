<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="j6_st9bwe"/><path class="ltadzzb7p"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:race-weekend" {...props}></Icon>
<style>
:global(.j6_st9bwe) {
  d: path("M3 3.5h18v18H3Zm5-1v3m8-3v3");
}

:global(.ltadzzb7p) {
  d: path("M7 18V8.5h10V14H7m5-5.5V14m-5-2.75h10");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
