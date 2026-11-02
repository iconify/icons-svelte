<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i3xg1kb-h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:file-minus-corner-fill-sharp" {...props}></Icon>
<style>
:global(.i3xg1kb-h) {
  fill: currentColor;
  d: path("M10 10v11a1 1 0 0 1-1 1H5a1 1 0 0 1-1-1V3a1 1 0 0 1 1-1h8c.265 0 .52.105.707.293l6 6A1 1 0 0 1 19 10Zm3-6v4h4Zm8 11a1 1 0 0 1 0 2h-8a1 1 0 0 1 0-2Z");
}

</style>
