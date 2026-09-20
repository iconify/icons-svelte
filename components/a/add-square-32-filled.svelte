<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="omscydbsy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:add-square-32-filled" {...props}></Icon>
<style>
:global(.omscydbsy) {
  fill: currentColor;
  d: path("M7.5 3A4.5 4.5 0 0 0 3 7.5v17A4.5 4.5 0 0 0 7.5 29h17a4.5 4.5 0 0 0 4.5-4.5v-17A4.5 4.5 0 0 0 24.5 3zM16 8a1 1 0 0 1 1 1v6h6a1 1 0 1 1 0 2h-6v6a1 1 0 1 1-2 0v-6H9a1 1 0 1 1 0-2h6V9a1 1 0 0 1 1-1");
}

</style>
