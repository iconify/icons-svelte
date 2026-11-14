<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ci_fbibnp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:cell-sector" {...props}></Icon>
<style>
:global(.ci_fbibnp) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 21.5L8.5 8l3 13.5M7 15h3m1.531-8.75a3.5 3.5 0 0 1 0 3.5m3.031-5.25a7 7 0 0 1 0 7m3.031-8.75a10.5 10.5 0 0 1 0 10.5");
}

</style>
