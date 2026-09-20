<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="y0jyw_4sp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:circle-12-filled" {...props}></Icon>
<style>
:global(.y0jyw_4sp) {
  fill: currentColor;
  d: path("M6 1a5 5 0 1 0 0 10A5 5 0 0 0 6 1");
}

</style>
