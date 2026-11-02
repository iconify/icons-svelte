<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iqt9k4bgx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:music-note-fill-sharp" {...props}></Icon>
<style>
:global(.iqt9k4bgx) {
  fill: currentColor;
  d: path("M11 4a1 1 0 0 1 1.447-.894l6 3a1 1 0 1 1-.894 1.788L13 5.618V17a4.001 4.001 0 1 1-2-3.465Z");
}

</style>
