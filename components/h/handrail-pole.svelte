<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wgzi4oi5h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:handrail-pole" {...props}></Icon>
<style>
:global(.wgzi4oi5h) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 19.5V5a2 2 0 0 1 2-2h3a2 2 0 0 1 2 2v3M7 19.5h6v2H7Z");
}

</style>
