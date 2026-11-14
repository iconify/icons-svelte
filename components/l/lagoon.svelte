<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="om54-ta-b"/><path class="w7jsxzbrs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:lagoon" {...props}></Icon>
<style>
:global(.om54-ta-b) {
  d: path("M12 12.75Q11.5 8.5 13.5 5m0 0q-3.5-3-7 1m7-1Q18 2.5 20 7");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.w7jsxzbrs) {
  d: path("M7.5 14.5q4.5-3.5 9 0M3 17.75q2.25-1 4.5 0t4.5 0t4.5 0t4.5 0m-15.5 3.5q2.25-1 4.5 0t4.5 0t4.5 0");
}

</style>
