<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="rqekgqf0e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:presence-busy-20-filled" {...props}></Icon>
<style>
:global(.rqekgqf0e) {
  fill: currentColor;
  d: path("M20 10c0 5.523-4.477 10-10 10S0 15.523 0 10S4.477 0 10 0s10 4.477 10 10");
}

</style>
