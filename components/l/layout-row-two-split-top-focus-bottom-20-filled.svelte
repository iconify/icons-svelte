<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="l2081-bpg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:layout-row-two-split-top-focus-bottom-20-filled" {...props}></Icon>
<style>
:global(.l2081-bpg) {
  fill: currentColor;
  d: path("M3 6a3 3 0 0 1 3-3h8a3 3 0 0 1 3 3v8a3 3 0 0 1-3 3H6a3 3 0 0 1-3-3zm3-2a2 2 0 0 0-2 2v4h5.5V4zm4.5 0v6H16V6a2 2 0 0 0-2-2z");
}

</style>
