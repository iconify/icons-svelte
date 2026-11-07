<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y_lh41bbu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:file-type-fill-sharp" {...props}></Icon>
<style>
:global(.y_lh41bbu) {
  fill: currentColor;
  d: path("M13 2c.265 0 .52.105.707.293l6 6A1 1 0 0 1 20 9v12a1 1 0 0 1-1 1H5a1 1 0 0 1-1-1V3a1 1 0 0 1 1-1Zm0 7h5l-5-5Zm-4 2a1 1 0 0 0 0 2h2v5a1 1 0 0 0 2 0v-5h2a1 1 0 0 0 0-2Z");
}

</style>
