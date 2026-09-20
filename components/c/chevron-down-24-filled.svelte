<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i6b7c7bht"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:chevron-down-24-filled" {...props}></Icon>
<style>
:global(.i6b7c7bht) {
  fill: currentColor;
  d: path("M4.293 8.293a1 1 0 0 1 1.414 0L12 14.586l6.293-6.293a1 1 0 1 1 1.414 1.414l-7 7a1 1 0 0 1-1.414 0l-7-7a1 1 0 0 1 0-1.414");
}

</style>
