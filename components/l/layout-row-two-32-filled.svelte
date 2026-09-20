<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="xqock-bmk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:layout-row-two-32-filled" {...props}></Icon>
<style>
:global(.xqock-bmk) {
  fill: currentColor;
  d: path("M7.5 3A4.5 4.5 0 0 0 3 7.5V15h26V7.5A4.5 4.5 0 0 0 24.5 3zM29 17H3v7.5A4.5 4.5 0 0 0 7.5 29h17a4.5 4.5 0 0 0 4.5-4.5z");
}

</style>
