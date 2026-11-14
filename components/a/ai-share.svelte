<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k4w993bec"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:ai-share" {...props}></Icon>
<style>
:global(.k4w993bec) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 12a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0m11 6.5a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0m2.75-16c.1 2 1.2 2.9 3 3c-1.8.1-2.9 1-3 3c-.1-2-1.2-2.9-3-3c1.8-.1 2.9-1 3-3m-8.5 8l5.75-3.25M9 13.5l6 3.5");
}

</style>
