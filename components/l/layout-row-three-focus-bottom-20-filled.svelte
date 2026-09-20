<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="c7wvdfngd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:layout-row-three-focus-bottom-20-filled" {...props}></Icon>
<style>
:global(.c7wvdfngd) {
  fill: currentColor;
  d: path("M6 17a3 3 0 0 1-3-3V6a3 3 0 0 1 3-3h8a3 3 0 0 1 3 3v8a3 3 0 0 1-3 3zm10-9H4v4h12zm0-1V6a2 2 0 0 0-2-2H6a2 2 0 0 0-2 2v1z");
}

</style>
