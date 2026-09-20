<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="b0n-sxznw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:record-stop-20-regular" {...props}></Icon>
<style>
:global(.b0n-sxznw) {
  fill: currentColor;
  d: path("M10 3a7 7 0 1 0 0 14a7 7 0 0 0 0-14m-8 7a8 8 0 1 1 16 0a8 8 0 0 1-16 0m5-2a1 1 0 0 1 1-1h4a1 1 0 0 1 1 1v4a1 1 0 0 1-1 1H8a1 1 0 0 1-1-1z");
}

</style>
