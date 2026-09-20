<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="je0f80bbx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:record-32-filled" {...props}></Icon>
<style>
:global(.je0f80bbx) {
  fill: currentColor;
  d: path("M16 2C8.268 2 2 8.268 2 16s6.268 14 14 14s14-6.268 14-14S23.732 2 16 2m0 23a9 9 0 1 1 0-18a9 9 0 0 1 0 18");
}

</style>
