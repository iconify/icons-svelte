<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ackfdybph"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:dialpad-32-regular" {...props}></Icon>
<style>
:global(.ackfdybph) {
  fill: currentColor;
  d: path("M11 5a2 2 0 1 1-4 0a2 2 0 0 1 4 0m0 7a2 2 0 1 1-4 0a2 2 0 0 1 4 0m0 7a2 2 0 1 1-4 0a2 2 0 0 1 4 0m7-14a2 2 0 1 1-4 0a2 2 0 0 1 4 0m0 7a2 2 0 1 1-4 0a2 2 0 0 1 4 0m0 7a2 2 0 1 1-4 0a2 2 0 0 1 4 0m0 7a2 2 0 1 1-4 0a2 2 0 0 1 4 0m7-21a2 2 0 1 1-4 0a2 2 0 0 1 4 0m0 7a2 2 0 1 1-4 0a2 2 0 0 1 4 0m0 7a2 2 0 1 1-4 0a2 2 0 0 1 4 0");
}

</style>
