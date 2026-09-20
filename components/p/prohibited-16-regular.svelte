<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="toh0lpxph"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:prohibited-16-regular" {...props}></Icon>
<style>
:global(.toh0lpxph) {
  fill: currentColor;
  d: path("M11.875 3.418a6 6 0 0 0-8.457 8.457zm.707.707l-8.457 8.457a6 6 0 0 0 8.457-8.457M3.05 3.05a7 7 0 1 1 9.9 9.9a7 7 0 0 1-9.9-9.9");
}

</style>
