<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lqs9esbfx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:insulated-flask" {...props}></Icon>
<style>
:global(.lqs9esbfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 10.5v1l-3 2.5v5A2.5 2.5 0 0 0 9 21.5h6a2.5 2.5 0 0 0 2.5-2.5v-5l-3-2.5v-1m-7-2.75h9l-1 2.75h-7ZM10 5c-1-1 1-1.5 0-2.5M14 5c-1-1 1-1.5 0-2.5");
}

</style>
