<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wtris4ith"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:gravestone-cross" {...props}></Icon>
<style>
:global(.wtris4ith) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 18V9a6 6 0 0 1 12 0v9M5.25 18h13.5a1.75 1.75 0 0 1 1.75 1.75a1.75 1.75 0 0 1-1.75 1.75H5.25a1.75 1.75 0 0 1-1.75-1.75A1.75 1.75 0 0 1 5.25 18M12 6.5V15M9 9.5h6");
}

</style>
