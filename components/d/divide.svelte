<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v0yn-6ajx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:divide" {...props}></Icon>
<style>
:global(.v0yn-6ajx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 12h14m-7-5.5h.01m-.01 11h.01");
}

</style>
