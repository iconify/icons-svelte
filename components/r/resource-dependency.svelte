<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ihfxt1b2n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:resource-dependency" {...props}></Icon>
<style>
:global(.ihfxt1b2n) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 5.5a3 3 0 1 0 6 0a3 3 0 1 0-6 0M15 12a3 3 0 1 0 6 0a3 3 0 1 0-6 0M3 18.5a3 3 0 1 0 6 0a3 3 0 1 0-6 0M8.75 7l6.5 3.5M8.75 17l6.5-3.5M6 8.5v7");
}

</style>
