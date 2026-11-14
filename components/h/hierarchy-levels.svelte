<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s626lvbfx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:hierarchy-levels" {...props}></Icon>
<style>
:global(.s626lvbfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12 3l2.5 5h-5Zm-4 8h8l2.5 4.5h-13Zm-4 7.5h16l1.5 3h-19Z");
}

</style>
