<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="yp82w0b0n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:arrow-down-right-20-filled" {...props}></Icon>
<style>
:global(.yp82w0b0n) {
  fill: currentColor;
  d: path("M8 16.25c0 .414.335.75.75.75h7.5a.75.75 0 0 0 .75-.75v-7.5a.75.75 0 1 0-1.5 0v5.69L4.28 3.22a.75.75 0 1 0-1.06 1.06L14.44 15.5H8.75a.75.75 0 0 0-.75.75");
}

</style>
