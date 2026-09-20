<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="q3dkf6bdi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:layout-cell-four-focus-top-left-20-filled" {...props}></Icon>
<style>
:global(.q3dkf6bdi) {
  fill: currentColor;
  d: path("M6 3a3 3 0 0 0-3 3v8a3 3 0 0 0 3 3h8a3 3 0 0 0 3-3V6a3 3 0 0 0-3-3zm-2 7.5h5.5V16H6a2 2 0 0 1-2-2zm12 0V14a2 2 0 0 1-2 2h-3.5v-5.5zm-5.5-1V4H14a2 2 0 0 1 2 2v3.5z");
}

</style>
