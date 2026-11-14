<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="as1lncb3n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:connection-lost" {...props}></Icon>
<style>
:global(.as1lncb3n) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2 12a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0m15 0a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0M7 12h1.5m7 0H17m-6.5-1.5l3 3m0-3l-3 3");
}

</style>
