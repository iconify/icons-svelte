<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="k899psble"/><path class="u1t2crblf"/><path class="ha8prubvr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:data-field" {...props}></Icon>
<style>
:global(.ha8prubvr) {
  d: path("M6.5 13v4");
}

:global(.k899psble) {
  d: path("M2.5 10h19v10h-19Z");
}

:global(.u1t2crblf) {
  fill: currentColor;
  d: path("M2.5 3.5H11V7H2.5Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
