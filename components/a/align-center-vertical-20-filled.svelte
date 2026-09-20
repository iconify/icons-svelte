<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="tl0qhr-xq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:align-center-vertical-20-filled" {...props}></Icon>
<style>
:global(.tl0qhr-xq) {
  fill: currentColor;
  d: path("M10.5 18a.5.5 0 0 1-.5-.5V16H8a2 2 0 0 1-2-2v-1a2 2 0 0 1 2-2h2V9H6a2 2 0 0 1-2-2V6a2 2 0 0 1 2-2h4V2.5a.5.5 0 0 1 1 0V4h4a2 2 0 0 1 2 2v1a2 2 0 0 1-2 2h-4v2h2a2 2 0 0 1 2 2v1a2 2 0 0 1-2 2h-2v1.5a.5.5 0 0 1-.5.5");
}

</style>
