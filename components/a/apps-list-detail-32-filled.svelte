<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="llwc4vb8t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:apps-list-detail-32-filled" {...props}></Icon>
<style>
:global(.llwc4vb8t) {
  fill: currentColor;
  d: path("M2 8a3 3 0 0 1 3-3h3a3 3 0 0 1 3 3v3a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3zm13-2a1 1 0 1 0 0 2h14a1 1 0 1 0 0-2zm0 13a1 1 0 1 0 0 2h14a1 1 0 1 0 0-2zm-1-8a1 1 0 0 1 1-1h9a1 1 0 1 1 0 2h-9a1 1 0 0 1-1-1m1 12a1 1 0 1 0 0 2h9a1 1 0 1 0 0-2zM5 18a3 3 0 0 0-3 3v3a3 3 0 0 0 3 3h3a3 3 0 0 0 3-3v-3a3 3 0 0 0-3-3z");
}

</style>
