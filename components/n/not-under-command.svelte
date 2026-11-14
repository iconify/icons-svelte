<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jgt75_-hl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:not-under-command" {...props}></Icon>
<style>
:global(.jgt75_-hl) {
  fill: currentColor;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 6.5a4 4 0 1 0 8 0a4 4 0 1 0-8 0m0 11a4 4 0 1 0 8 0a4 4 0 1 0-8 0");
}

</style>
