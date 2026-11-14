<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lwo0jhves"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:more-horizontal" {...props}></Icon>
<style>
:global(.lwo0jhves) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 12a1 1 0 1 0 2 0a1 1 0 1 0-2 0M11 12a1 1 0 1 0 2 0a1 1 0 1 0-2 0m7.25 0a1 1 0 1 0 2 0a1 1 0 1 0-2 0");
}

</style>
