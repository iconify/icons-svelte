<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jz10s5bdu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:bazaar-stall" {...props}></Icon>
<style>
:global(.jz10s5bdu) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3 9l1.5-5h15L21 9Zm0 0a3 3 0 0 0 6 0a3 3 0 0 0 6 0a3 3 0 0 0 6 0M5 12v8.5M19 12v8.5M7.5 17a2 2 0 1 0 4 0a2 2 0 1 0-4 0m5 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0");
}

</style>
