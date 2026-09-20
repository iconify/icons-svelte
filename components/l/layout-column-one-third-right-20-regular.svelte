<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="w1jyo18xm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:layout-column-one-third-right-20-regular" {...props}></Icon>
<style>
:global(.w1jyo18xm) {
  fill: currentColor;
  d: path("M6 3a3 3 0 0 0-3 3v8a3 3 0 0 0 3 3h8a3 3 0 0 0 3-3V6a3 3 0 0 0-3-3zM4 6a2 2 0 0 1 2-2h6v12H6a2 2 0 0 1-2-2zm9 10V4h1a2 2 0 0 1 2 2v8a2 2 0 0 1-2 2z");
}

</style>
