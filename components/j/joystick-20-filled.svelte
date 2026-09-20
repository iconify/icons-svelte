<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="vrke-vbad"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:joystick-20-filled" {...props}></Icon>
<style>
:global(.vrke-vbad) {
  fill: currentColor;
  d: path("M10.5 7.959a3 3 0 1 0-1 0V11h-2A1.5 1.5 0 0 0 6 12.5v.5h8v-.5a1.5 1.5 0 0 0-1.5-1.5h-2zM3 16a2 2 0 0 1 2-2h10a2 2 0 0 1 2 2v1.5a.5.5 0 0 1-.5.5h-13a.5.5 0 0 1-.5-.5z");
}

</style>
