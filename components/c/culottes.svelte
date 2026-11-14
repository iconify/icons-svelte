<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kv4ztl0ze"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:culottes" {...props}></Icon>
<style>
:global(.kv4ztl0ze) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 3.5h10v3l3.5 13h-7L12 9.5l-1.5 10h-7L7 6.5Zm0 3h10");
}

</style>
