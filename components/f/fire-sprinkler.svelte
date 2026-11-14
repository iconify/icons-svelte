<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t0f8lumur"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:fire-sprinkler" {...props}></Icon>
<style>
:global(.t0f8lumur) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 3v5M8.5 8h7L14 12.5h-4ZM8 15.5l-1.5 3m5.5-3v4m4-4l1.5 3");
}

</style>
