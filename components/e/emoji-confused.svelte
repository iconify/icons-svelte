<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jvbm6uw5t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:emoji-confused" {...props}></Icon>
<style>
:global(.jvbm6uw5t) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 12a9.5 9.5 0 1 0 19 0a9.5 9.5 0 1 0-19 0M9 10h.01M15 10h.01M8.5 16.5l7-2");
}

</style>
