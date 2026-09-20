<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xiujhq70r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:pause-circle-24-regular" {...props}></Icon>
<style>
:global(.xiujhq70r) {
  fill: currentColor;
  d: path("M10.5 8.25a.75.75 0 0 0-1.5 0v7.5a.75.75 0 0 0 1.5 0zm4.5 0a.75.75 0 0 0-1.5 0v7.5a.75.75 0 0 0 1.5 0zM12 2C6.477 2 2 6.477 2 12s4.477 10 10 10s10-4.477 10-10S17.523 2 12 2M3.5 12a8.5 8.5 0 1 1 17 0a8.5 8.5 0 0 1-17 0");
}

</style>
