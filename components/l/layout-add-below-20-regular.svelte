<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="pxgldg3ca"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:layout-add-below-20-regular" {...props}></Icon>
<style>
:global(.pxgldg3ca) {
  fill: currentColor;
  d: path("M16.5 16a.5.5 0 0 1 0 1h-13a.5.5 0 0 1 0-1zM14 3a3 3 0 0 1 3 3v5.5a.5.5 0 0 1-.5.5h-13a.5.5 0 0 1-.5-.5V6a3 3 0 0 1 3-3zM6 4a2 2 0 0 0-2 2v5h12V6a2 2 0 0 0-2-2z");
}

</style>
