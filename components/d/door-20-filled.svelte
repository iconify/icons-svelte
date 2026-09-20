<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="is-g89sui"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:door-20-filled" {...props}></Icon>
<style>
:global(.is-g89sui) {
  fill: currentColor;
  d: path("M14 2a2 2 0 0 1 2 2v12a2 2 0 0 1-2 2H6a2 2 0 0 1-2-2V4a2 2 0 0 1 2-2zM7 9a1 1 0 1 0 0 2a1 1 0 0 0 0-2");
}

</style>
