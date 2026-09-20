<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xah9ui_8r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:chevron-left-24-filled" {...props}></Icon>
<style>
:global(.xah9ui_8r) {
  fill: currentColor;
  d: path("M15.707 4.293a1 1 0 0 1 0 1.414L9.414 12l6.293 6.293a1 1 0 0 1-1.414 1.414l-7-7a1 1 0 0 1 0-1.414l7-7a1 1 0 0 1 1.414 0");
}

</style>
