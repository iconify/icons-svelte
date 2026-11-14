<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ioogn5bkv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:banana" {...props}></Icon>
<style>
:global(.ioogn5bkv) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 5c-1.5 7 3 15 13 14.5c2-.1 2.5-2 1-2.5c-6.5-1-10-6-11.5-12.5Z");
}

</style>
