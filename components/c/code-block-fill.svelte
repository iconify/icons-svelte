<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tjd3_jb6h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:code-block-fill" {...props}></Icon>
<style>
:global(.tjd3_jb6h) {
  fill: currentColor;
  d: path("M2 5a3 3 0 0 1 3-3h14a3 3 0 0 1 3 3v14a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3Zm8.707 4.707a.999.999 0 1 0-1.414-1.414l-3 3a.997.997 0 0 0 0 1.414l3 3a.999.999 0 1 0 1.414-1.414L8.414 12Zm4-1.414a.999.999 0 1 0-1.414 1.414L15.586 12l-2.293 2.293a.999.999 0 1 0 1.414 1.414l3-3a1 1 0 0 0 0-1.414Z");
}

</style>
