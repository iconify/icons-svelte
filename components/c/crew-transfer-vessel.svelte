<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fq0yysbgu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:crew-transfer-vessel" {...props}></Icon>
<style>
:global(.fq0yysbgu) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 7h15L16 11H4.5ZM7 7V3h6.5l2 4m-13 7.5q2.5-2 5 0q2.096 1.677 4.192.542M18 16.5v5.25m0-5.25l1.75-3m-1.75 3l1.75 3m-1.75-3h-3.5");
}

</style>
