<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i69a59b6i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:check" {...props}></Icon>
<style>
:global(.i69a59b6i) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 12.5L9.5 18l11-11");
}

</style>
