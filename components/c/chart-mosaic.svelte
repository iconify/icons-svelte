<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o9rynodjd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:chart-mosaic" {...props}></Icon>
<style>
:global(.o9rynodjd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 2.5H11v19H2.5Zm11 0h8V12h-8Zm0 12h2.75v7H13.5Zm5.25 0h2.75v7h-2.75Z");
}

</style>
