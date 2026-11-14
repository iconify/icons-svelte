<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sppog9bes"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:alpha-symbol" {...props}></Icon>
<style>
:global(.sppog9bes) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M20.5 4c-2 7-4 16-10 16c-4.5 0-7-3.5-7-8s2.5-8 7-8c6 0 8 9 10 16");
}

</style>
