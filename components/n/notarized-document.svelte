<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="p26mcfbte"/><path class="j_hrww23d"/><path class="wvsg4sbjd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:notarized-document" {...props}></Icon>
<style>
:global(.j_hrww23d) {
  d: path("m16.5 10.5l.841.861l1.159-.325l.298 1.166l1.166.298l-.325 1.159l.861.841l-.861.841l.325 1.159l-1.166.298l-.298 1.166l-1.159-.325l-.841.861l-.841-.861l-1.159.325l-.298-1.166l-1.166-.298l.325-1.159l-.861-.841l.861-.841l-.325-1.159l1.166-.298l.298-1.166l1.159.325Z");
}

:global(.p26mcfbte) {
  d: path("M11.7 20H3.5V2.5H18v5.6M6.5 6.5h8m-8 3.5h4");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.wvsg4sbjd) {
  d: path("m14.75 18l-.5 3.75l2.25-1.25l2.25 1.25l-.5-3.75");
}

</style>
