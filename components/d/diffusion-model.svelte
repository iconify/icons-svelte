<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mm2ptg3th"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:diffusion-model" {...props}></Icon>
<style>
:global(.mm2ptg3th) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 7h7A1.5 1.5 0 0 1 13 8.5v7a1.5 1.5 0 0 1-1.5 1.5h-7A1.5 1.5 0 0 1 3 15.5v-7A1.5 1.5 0 0 1 4.5 7m12 1h.01m-.01 4h.01m-.01 4h.01m3.99-6h.01m-.01 4h.01");
}

</style>
