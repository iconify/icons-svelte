<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="es8p6ybud"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:pole-saw" {...props}></Icon>
<style>
:global(.es8p6ybud) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3 21l9.5-9.5m-1-1l8-8l2 2v2h-2v2h-2v2h-2v2h-2Z");
}

</style>
