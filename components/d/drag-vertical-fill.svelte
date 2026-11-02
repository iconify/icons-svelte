<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o77se9lzf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:drag-vertical-fill" {...props}></Icon>
<style>
:global(.o77se9lzf) {
  fill: currentColor;
  d: path("M7.158 5.221a2 2 0 1 1 3.684 1.558a2 2 0 0 1-3.684-1.558m6 0a2 2 0 1 1 3.684 1.558a2 2 0 0 1-3.684-1.558m-6 6a2 2 0 1 1 3.684 1.558a2 2 0 0 1-3.684-1.558m6 0a2 2 0 1 1 3.684 1.558a2 2 0 0 1-3.684-1.558m-6 6a2 2 0 1 1 3.684 1.558a2 2 0 0 1-3.684-1.558m6 0a2 2 0 1 1 3.684 1.558a2 2 0 0 1-3.684-1.558");
}

</style>
