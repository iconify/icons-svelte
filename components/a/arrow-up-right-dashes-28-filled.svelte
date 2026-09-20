<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":28,"height":28};
const content = `<path class="u9w1e9fxd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:arrow-up-right-dashes-28-filled" {...props}></Icon>
<style>
:global(.u9w1e9fxd) {
  fill: currentColor;
  d: path("M23 15a1 1 0 1 0 2 0V4a1 1 0 0 0-1-1H13a1 1 0 1 0 0 2h8.586l-4.293 4.293a1 1 0 0 0 1.414 1.414L23 6.414zM8.707 20.707a1 1 0 1 0-1.414-1.414l-4 4a1 1 0 1 0 1.414 1.414zm7-8.414a1 1 0 0 1 0 1.414l-4 4a1 1 0 0 1-1.414-1.414l4-4a1 1 0 0 1 1.414 0");
}

</style>
