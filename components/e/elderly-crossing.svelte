<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uaruy1bhz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:elderly-crossing" {...props}></Icon>
<style>
:global(.uaruy1bhz) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.25 4.5a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0m.25 4.25L4.75 14l1.75 7m-1.75-7L3 21M6.5 8.75l3 3.25v9m7.25-16.5a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0M17 8.75L15.25 14L17 21m-1.75-7l-1.75 7M17 8.75L20 12v9");
}

</style>
