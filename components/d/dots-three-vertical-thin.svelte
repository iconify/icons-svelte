<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="s9gljrbck"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:dots-three-vertical-thin" {...props}></Icon>
<style>
:global(.s9gljrbck) {
  fill: currentColor;
  d: path("M120 60a8 8 0 1 1 8 8a8 8 0 0 1-8-8m8 60a8 8 0 1 0 8 8a8 8 0 0 0-8-8m0 68a8 8 0 1 0 8 8a8 8 0 0 0-8-8");
}

</style>
