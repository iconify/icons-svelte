<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="m0oajvfgn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:presence-busy-12-filled" {...props}></Icon>
<style>
:global(.m0oajvfgn) {
  fill: currentColor;
  d: path("M12 6A6 6 0 1 1 0 6a6 6 0 0 1 12 0");
}

</style>
