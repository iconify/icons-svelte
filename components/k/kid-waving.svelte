<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vx925-bcs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:kid-waving" {...props}></Icon>
<style>
:global(.vx925-bcs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 6.5a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0m-3 15C4 17 6.75 14 10.5 14s6.5 3 6.5 7.5M14 15l5.5-9");
}

</style>
