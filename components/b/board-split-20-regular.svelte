<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="cvd_t124v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:board-split-20-regular" {...props}></Icon>
<style>
:global(.cvd_t124v) {
  fill: currentColor;
  d: path("M3 6a3 3 0 0 1 3-3h8a3 3 0 0 1 3 3v8a3 3 0 0 1-3 3H6a3 3 0 0 1-3-3zm1 4v4a2 2 0 0 0 2 2h5v-6zm7-1V4H6a2 2 0 0 0-2 2v3zm1 7h2a2 2 0 0 0 2-2v-1h-4zm4-9V6a2 2 0 0 0-2-2h-2v3zm0 1h-4v4h4z");
}

</style>
