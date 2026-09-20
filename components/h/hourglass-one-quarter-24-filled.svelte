<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x1f8j-6kp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:hourglass-one-quarter-24-filled" {...props}></Icon>
<style>
:global(.x1f8j-6kp) {
  fill: currentColor;
  d: path("M7.92 16a3.24 3.24 0 0 0-1.42 2.65v.6a.25.25 0 0 0 .25.25h10.5a.25.25 0 0 0 .25-.25v-.6A3.24 3.24 0 0 0 16.08 16z");
}

</style>
