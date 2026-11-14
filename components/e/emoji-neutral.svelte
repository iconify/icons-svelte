<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j9mzzbceh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:emoji-neutral" {...props}></Icon>
<style>
:global(.j9mzzbceh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 12a9.5 9.5 0 1 0 19 0a9.5 9.5 0 1 0-19 0M9 10h.01M15 10h.01M8.5 15.5h7");
}

</style>
