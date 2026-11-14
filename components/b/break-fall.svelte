<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="qdzqazyhg"/><path class="tifnew2bo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:break-fall" {...props}></Icon>
<style>
:global(.qdzqazyhg) {
  d: path("M5 12.5a7 7 0 0 1 14 0");
}

:global(.tifnew2bo) {
  d: path("m16.5 10l2.5 2.5l2.5-2.5M3 16h18v3.5H3Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
