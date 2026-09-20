<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="pvlnqtbaa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:layout-column-two-20-regular" {...props}></Icon>
<style>
:global(.pvlnqtbaa) {
  fill: currentColor;
  d: path("M6 3a3 3 0 0 0-3 3v8a3 3 0 0 0 3 3h8a3 3 0 0 0 3-3V6a3 3 0 0 0-3-3zM4 6a2 2 0 0 1 2-2h3.5v12H6a2 2 0 0 1-2-2zm6.5 10V4H14a2 2 0 0 1 2 2v8a2 2 0 0 1-2 2z");
}

</style>
