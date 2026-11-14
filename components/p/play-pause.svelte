<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oqse0n9wf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:play-pause" {...props}></Icon>
<style>
:global(.oqse0n9wf) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m5.8 8.1l3.333 2.5a1.75 1.75 0 0 1 0 2.8L5.8 15.9A1.75 1.75 0 0 1 3 14.5v-5a1.75 1.75 0 0 1 2.8-1.4M15 6v12m5-12v12");
}

</style>
