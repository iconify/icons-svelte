<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="liop60bkv"/><path class="e0smqgaxp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:insurance-anchor" {...props}></Icon>
<style>
:global(.e0smqgaxp) {
  d: path("m3 15l1.5-1.5L6 15m12 0l1.5-1.5L21 15");
}

:global(.liop60bkv) {
  d: path("M10 4.75a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm2 2V21m-7.5-7.5C4.5 17.75 8 21 12 21s7.5-3.25 7.5-7.5m-11-3.25h7");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
