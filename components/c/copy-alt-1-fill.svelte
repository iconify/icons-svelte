<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xz9akfbmx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:copy-alt-1-fill" {...props}></Icon>
<style>
:global(.xz9akfbmx) {
  fill: currentColor;
  d: path("M2 11a3 3 0 0 1 3-3h3V5a3 3 0 0 1 3-3h8a3 3 0 0 1 3 3v8a3 3 0 0 1-3 3h-3v3a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3Zm17 3a1 1 0 0 0 1-1V5a1 1 0 0 0-1-1h-8a.997.997 0 0 0-1 1v3h3a3 3 0 0 1 3 3v3Z");
}

</style>
