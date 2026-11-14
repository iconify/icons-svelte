<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j6cusf80j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:dog-paw-print" {...props}></Icon>
<style>
:global(.j6cusf80j) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 12c2.5 0 6 4 6 6.5c0 2-1.5 2.5-3 2.5c-1 0-2-.5-3-.5s-2 .5-3 .5c-1.5 0-3-.5-3-2.5C6 16 9.5 12 12 12M2 12a2 2.5 0 1 0 4 0a2 2.5 0 1 0-4 0m4.5-6a2 2.75 0 1 0 4 0a2 2.75 0 1 0-4 0m7 0a2 2.75 0 1 0 4 0a2 2.75 0 1 0-4 0m4.5 6a2 2.5 0 1 0 4 0a2 2.5 0 1 0-4 0");
}

</style>
