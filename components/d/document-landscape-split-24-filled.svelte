<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y4aa5fble"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:document-landscape-split-24-filled" {...props}></Icon>
<style>
:global(.y4aa5fble) {
  fill: currentColor;
  d: path("M10.5 4H4a2 2 0 0 0-2 2v12a2 2 0 0 0 2 2h6.5zM12 20h8a2 2 0 0 0 2-2v-6h-6a2 2 0 0 1-2-2V4h-2zm4-9.5h5.5l-6-6V10a.5.5 0 0 0 .5.5");
}

</style>
