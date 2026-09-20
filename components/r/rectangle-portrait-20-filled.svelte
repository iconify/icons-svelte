<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="fsxm7vbwq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:rectangle-portrait-20-filled" {...props}></Icon>
<style>
:global(.fsxm7vbwq) {
  fill: currentColor;
  d: path("M4 15a3 3 0 0 0 3 3h6a3 3 0 0 0 3-3V5a3 3 0 0 0-3-3H7a3 3 0 0 0-3 3z");
}

</style>
