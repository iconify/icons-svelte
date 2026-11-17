<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tru75abhp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:file-zap-corner-fill-sharp" {...props}></Icon>
<style>
:global(.tru75abhp) {
  fill: currentColor;
  d: path("M13 2c.265 0 .52.105.707.293l6 6A1 1 0 0 1 19 10h-9v11a1 1 0 0 1-1 1H5a1 1 0 0 1-1-1V3a1 1 0 0 1 1-1Zm0 6h4l-4-4Zm7 8a1.002 1.002 0 0 1 .707 1.707l-4 4a.999.999 0 1 1-1.414-1.414L17.586 18H15a1.002 1.002 0 0 1-.707-1.707l4-4a.999.999 0 1 1 1.414 1.414L17.414 16Z");
}

</style>
