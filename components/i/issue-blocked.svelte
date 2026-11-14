<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r06hkxbyo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:issue-blocked" {...props}></Icon>
<style>
:global(.r06hkxbyo) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11 19a8 8 0 1 1 8-8m-8 0h.01m3.74 7a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0m1 2.25l4.5-4.5");
}

</style>
