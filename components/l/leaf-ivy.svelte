<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uzxy5r3cg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:leaf-ivy" {...props}></Icon>
<style>
:global(.uzxy5r3cg) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12 2.5l3.25 5.75L21 10l-3.5 5l-5.5 3l-5.5-3L3 10l5.75-1.75ZM12 18v3.5m0-3.5V7.5");
}

</style>
