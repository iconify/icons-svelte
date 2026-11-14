<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t3209accm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:buttress" {...props}></Icon>
<style>
:global(.t3209accm) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.25 2.5h2A1.75 1.75 0 0 1 10 4.25v15.5a1.75 1.75 0 0 1-1.75 1.75h-2a1.75 1.75 0 0 1-1.75-1.75V4.25A1.75 1.75 0 0 1 6.25 2.5M10 7l9.5 14.5H10M4.5 9H10m-5.5 6H10");
}

</style>
