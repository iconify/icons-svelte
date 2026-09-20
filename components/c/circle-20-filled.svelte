<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ng7riubwb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:circle-20-filled" {...props}></Icon>
<style>
:global(.ng7riubwb) {
  fill: currentColor;
  d: path("M10 2a8 8 0 1 0 0 16a8 8 0 0 0 0-16");
}

</style>
