<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iwouvlbkx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:menu-collapse" {...props}></Icon>
<style>
:global(.iwouvlbkx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 12h17M8 3.5l4 4l4-4m-8 17l4-4l4 4");
}

</style>
