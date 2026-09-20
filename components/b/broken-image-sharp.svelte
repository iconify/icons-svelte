<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kbbxjvb6w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:broken-image-sharp" {...props}></Icon>
<style>
:global(.kbbxjvb6w) {
  fill: currentColor;
  d: path("M3 21v-8.6l3 3l4-4l4 4l4-4l3 3V21zM3 3h18v8.575l-3-3l-4 4l-4-4l-4 4l-3-3z");
}

</style>
