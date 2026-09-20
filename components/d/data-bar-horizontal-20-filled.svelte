<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="av_kt1b3x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:data-bar-horizontal-20-filled" {...props}></Icon>
<style>
:global(.av_kt1b3x) {
  fill: currentColor;
  d: path("M4 2a2 2 0 1 0 0 4h5a2 2 0 1 0 0-4zm0 6a2 2 0 1 0 0 4h8a2 2 0 1 0 0-4zm0 6a2 2 0 1 0 0 4h12a2 2 0 1 0 0-4z");
}

</style>
