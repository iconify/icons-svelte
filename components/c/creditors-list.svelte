<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kdgu2y04b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:creditors-list" {...props}></Icon>
<style>
:global(.kdgu2y04b) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 3.5h.01M4 9.5h.01m-.01 6h.01M8 3.5h12m-12 6h12m-12 6h3.5M15 21l5.25-5.25m-4-.25h4.25v4.25");
}

</style>
