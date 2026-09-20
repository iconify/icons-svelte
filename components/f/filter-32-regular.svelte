<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="qr9n71tzs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:filter-32-regular" {...props}></Icon>
<style>
:global(.qr9n71tzs) {
  fill: currentColor;
  d: path("M3 9a1 1 0 0 1 1-1h24a1 1 0 1 1 0 2H4a1 1 0 0 1-1-1m4 7a1 1 0 0 1 1-1h16a1 1 0 1 1 0 2H8a1 1 0 0 1-1-1m5 6a1 1 0 1 0 0 2h8a1 1 0 1 0 0-2z");
}

</style>
