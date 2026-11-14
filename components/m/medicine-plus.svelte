<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lzz75obeg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:medicine-plus" {...props}></Icon>
<style>
:global(.lzz75obeg) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M17.01 4.99za3 3 0 0 1 0 4.242L9.232 17.01a3 3 0 0 1-4.242 0a3 3 0 0 1 0-4.242l7.778-7.778a3 3 0 0 1 4.242 0M8.879 8.879l4.242 4.242M18 15v6m-3-3h6");
}

</style>
