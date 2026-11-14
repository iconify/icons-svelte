<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="egf4wbcxz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:competition-bench" {...props}></Icon>
<style>
:global(.egf4wbcxz) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 21.5V5m12 16.5V5M3.25 7.5h17.5m-17.5-3v6m17.5-6v6M3.5 14h17v3h-17Z");
}

</style>
