<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s2747tbis"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:greek-temple" {...props}></Icon>
<style>
:global(.s2747tbis) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3.5 9.5l8.5-5l8.5 5Zm0 11h17m-14-9v7m4-7v7m3.5-7v7m3.5-7v7");
}

</style>
