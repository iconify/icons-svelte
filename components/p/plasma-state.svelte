<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oej2s4bku"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:plasma-state" {...props}></Icon>
<style>
:global(.oej2s4bku) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13 3.5L9 12h6l-4 8.5m-8-14a2 2 0 1 0 4 0a2 2 0 1 0-4 0m0 11a2 2 0 1 0 4 0a2 2 0 1 0-4 0m16-11h.01m-.01 11h.01");
}

</style>
