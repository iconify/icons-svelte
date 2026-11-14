<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u-y03thpx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:insulator" {...props}></Icon>
<style>
:global(.u-y03thpx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 3h17M12 3v18.5M6.5 10q5.5-5 11 0Zm0 5q5.5-5 11 0Zm0 5q5.5-5 11 0Z");
}

</style>
