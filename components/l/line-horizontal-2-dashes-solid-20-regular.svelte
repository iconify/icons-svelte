<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="vb533kbcj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:line-horizontal-2-dashes-solid-20-regular" {...props}></Icon>
<style>
:global(.vb533kbcj) {
  fill: currentColor;
  d: path("M2.5 6a.5.5 0 0 0 0 1h3a.5.5 0 0 0 0-1zm6 0a.5.5 0 0 0 0 1h3a.5.5 0 0 0 0-1zm6 0a.5.5 0 0 0 0 1h3a.5.5 0 0 0 0-1zm-12 6a.5.5 0 0 0 0 1h15a.5.5 0 0 0 0-1z");
}

</style>
