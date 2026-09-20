<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="bf94_qbnb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:layout-column-three-focus-left-20-filled" {...props}></Icon>
<style>
:global(.bf94_qbnb) {
  fill: currentColor;
  d: path("M3 6a3 3 0 0 1 3-3h8a3 3 0 0 1 3 3v8a3 3 0 0 1-3 3H6a3 3 0 0 1-3-3zm9 10V4H8v12zm1 0h1a2 2 0 0 0 2-2V6a2 2 0 0 0-2-2h-1z");
}

</style>
