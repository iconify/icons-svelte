<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="asm-bcbca"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:presence-away-16-filled" {...props}></Icon>
<style>
:global(.asm-bcbca) {
  fill: currentColor;
  d: path("M8 16A8 8 0 1 0 8 0a8 8 0 0 0 0 16m.5-11.5v3.02l2.125 1.7a1 1 0 1 1-1.25 1.56l-2.5-2A1 1 0 0 1 6.5 8V4.5a1 1 0 0 1 2 0");
}

</style>
