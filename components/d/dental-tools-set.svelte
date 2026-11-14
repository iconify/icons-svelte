<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vg0__kbzf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:dental-tools-set" {...props}></Icon>
<style>
:global(.vg0__kbzf) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 6.5a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0M9 9l11 11M4 20L16 8l1.75-1.75c1.5-1.5.75-3.5-1-3");
}

</style>
