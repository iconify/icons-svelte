<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="turogi17x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:corner-desk" {...props}></Icon>
<style>
:global(.turogi17x) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 4.5h18V9H8v4.5H3Zm0 9v6M21 9v6.5");
}

</style>
