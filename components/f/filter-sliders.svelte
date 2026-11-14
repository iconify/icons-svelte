<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wryhkcbjc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:filter-sliders" {...props}></Icon>
<style>
:global(.wryhkcbjc) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 6h9m-6 6H9m.5 6h5m-1-12a2 2 0 1 0 4 0a2 2 0 1 0-4 0M10 12a2 2 0 1 0 4 0a2 2 0 1 0-4 0m5 0h2.5m0-6h3");
}

</style>
