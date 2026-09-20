<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ndgy1mbog"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:broken-image-outline-sharp" {...props}></Icon>
<style>
:global(.ndgy1mbog) {
  fill: currentColor;
  d: path("M4 20V4h16v16zm2-6.714l4-4l4 4l4-4l1 1V5H5v7.287zM5 19h14v-7.292l-1-1l-4 4l-4-4l-4 4l-1-1zm0 0v-7.292v1V5z");
}

</style>
