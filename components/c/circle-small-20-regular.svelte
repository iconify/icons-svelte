<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="g8_y08y0n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:circle-small-20-regular" {...props}></Icon>
<style>
:global(.g8_y08y0n) {
  fill: currentColor;
  d: path("M10 12a2 2 0 1 1 0-4a2 2 0 0 1 0 4m0 1a3 3 0 1 0 0-6a3 3 0 0 0 0 6");
}

</style>
