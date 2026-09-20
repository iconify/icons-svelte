<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="esc8_q6yg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:grid-circles-24-filled" {...props}></Icon>
<style>
:global(.esc8_q6yg) {
  fill: currentColor;
  d: path("M7 11a4 4 0 1 0 0-8a4 4 0 0 0 0 8m10 0a4 4 0 1 0 0-8a4 4 0 0 0 0 8m-6 6a4 4 0 1 1-8 0a4 4 0 0 1 8 0m6 4a4 4 0 1 0 0-8a4 4 0 0 0 0 8");
}

</style>
