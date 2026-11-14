<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="exfkhnmwk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:agent-critic" {...props}></Icon>
<style>
:global(.exfkhnmwk) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 7.5a4.5 4.5 0 1 0 9 0a4.5 4.5 0 1 0-9 0m-3 13v-1c0-3 3.25-5 7.5-5q2.25 0 3.75.75m0 2.75l2 2L21 15.75");
}

</style>
