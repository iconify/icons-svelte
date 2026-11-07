<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wcfd5bcjz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:music-note-double-fill-sharp" {...props}></Icon>
<style>
:global(.wcfd5bcjz) {
  fill: currentColor;
  d: path("M17.553 7.894L13 5.618v2.764l3.447 1.724a1 1 0 1 1-.894 1.788L13 10.618V17a4.001 4.001 0 1 1-2-3.465V4a1 1 0 0 1 1.447-.894l6 3a1 1 0 1 1-.894 1.788");
}

</style>
