<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="f7tm16h9z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:caret-right-16-filled" {...props}></Icon>
<style>
:global(.f7tm16h9z) {
  fill: currentColor;
  d: path("M7.571 11.84C6.908 12.298 6 11.827 6 11.024V4.975c0-.803.908-1.274 1.571-.816l3.784 2.617a1.486 1.486 0 0 1 0 2.447z");
}

</style>
