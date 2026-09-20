<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="qyoupod9r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:link-32-regular" {...props}></Icon>
<style>
:global(.qyoupod9r) {
  fill: currentColor;
  d: path("M2 16a7 7 0 0 1 7-7h4a1 1 0 1 1 0 2H9a5 5 0 0 0 0 10h4a1 1 0 1 1 0 2H9a7 7 0 0 1-7-7m28 0a7 7 0 0 0-7-7h-4a1 1 0 1 0 0 2h4a5 5 0 0 1 0 10h-4a1 1 0 1 0 0 2h4a7 7 0 0 0 7-7M9.5 15a1 1 0 1 0 0 2h13a1 1 0 1 0 0-2z");
}

</style>
