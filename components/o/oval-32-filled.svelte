<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="isq-yrb8m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:oval-32-filled" {...props}></Icon>
<style>
:global(.isq-yrb8m) {
  fill: currentColor;
  d: path("M12 6C6.477 6 2 10.477 2 16s4.477 10 10 10h8c5.523 0 10-4.477 10-10S25.523 6 20 6z");
}

</style>
