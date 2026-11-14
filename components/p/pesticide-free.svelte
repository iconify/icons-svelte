<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dsntq549d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:pesticide-free" {...props}></Icon>
<style>
:global(.dsntq549d) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 17.5c0-9 6-15 15-15c0 9-6 15-15 15Zm0 0L10 10m8.5 3.5l3 5a3 3 0 0 1-6 0Z");
}

</style>
