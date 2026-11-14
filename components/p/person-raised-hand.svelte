<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u89ad939h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:person-raised-hand" {...props}></Icon>
<style>
:global(.u89ad939h) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 4.25a2 2 0 1 0 4 0a2 2 0 1 0-4 0M10 8v6.5M7 21l3-6.5l3 6.5m-7-9.5l4-3h4.5L16 3");
}

</style>
