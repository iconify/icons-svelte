<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="bk_vk9i9f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:checkmark-circle-12-filled" {...props}></Icon>
<style>
:global(.bk_vk9i9f) {
  fill: currentColor;
  d: path("M1 6a5 5 0 1 1 10 0A5 5 0 0 1 1 6m7.354-.896a.5.5 0 1 0-.708-.708L5.5 6.543L4.354 5.396a.5.5 0 1 0-.708.708l1.5 1.5a.5.5 0 0 0 .708 0z");
}

</style>
