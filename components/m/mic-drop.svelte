<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="rd76scsbr"/><path class="yfhh6d95g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:mic-drop" {...props}></Icon>
<style>
:global(.rd76scsbr) {
  d: path("m13.652 2.139l5.196 3l-4 6.928l-5.196-3Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.yfhh6d95g) {
  d: path("m10.951 9.817l2.598 1.5L8.9 17.87l-1.3-.75ZM3 21.5h18M11.652 5.603l5.196 3");
}

</style>
