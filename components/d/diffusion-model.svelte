<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q8a2ciu9n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:diffusion-model" {...props}></Icon>
<style>
:global(.q8a2ciu9n) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 7h10v10H3Zm13.5 1h.01m-.01 4h.01m-.01 4h.01m3.99-6h.01m-.01 4h.01");
}

</style>
