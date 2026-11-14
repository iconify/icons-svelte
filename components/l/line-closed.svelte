<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j1ptbfbdl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:line-closed" {...props}></Icon>
<style>
:global(.j1ptbfbdl) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 9.5h3.1m7.8 0h8.1m-19 5h8.1m7.8 0h3.1M4 8v8m16-8v8M3.5 3.5l17 17");
}

</style>
