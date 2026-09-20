<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="kuk3qzbrc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:circle-multiple-concentric-20-regular" {...props}></Icon>
<style>
:global(.kuk3qzbrc) {
  fill: currentColor;
  d: path("M3 10a7 7 0 1 1 14 0a7 7 0 0 1-14 0m7-8a8 8 0 1 0 0 16a8 8 0 0 0 0-16m-4 8a4 4 0 1 1 8 0a4 4 0 0 1-8 0m4-5a5 5 0 1 0 0 10a5 5 0 0 0 0-10");
}

</style>
