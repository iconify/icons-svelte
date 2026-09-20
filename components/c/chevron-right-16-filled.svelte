<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="qv5oegcgg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:chevron-right-16-filled" {...props}></Icon>
<style>
:global(.qv5oegcgg) {
  fill: currentColor;
  d: path("M5.74 3.2a.75.75 0 0 0-.04 1.06L9.227 8L5.7 11.74a.75.75 0 1 0 1.1 1.02l4-4.25a.75.75 0 0 0 0-1.02l-4-4.25a.75.75 0 0 0-1.06-.04");
}

</style>
