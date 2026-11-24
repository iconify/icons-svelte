<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wigwasbkd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:file-warning-fill-sharp" {...props}></Icon>
<style>
:global(.wigwasbkd) {
  fill: currentColor;
  d: path("M13 2c.265 0 .52.105.707.293l6 6A1 1 0 0 1 20 9v12a1 1 0 0 1-1 1H5a1 1 0 0 1-1-1V3a1 1 0 0 1 1-1Zm0 7h5l-5-5Zm0 3a1 1 0 0 0-2 0v3a1 1 0 0 0 2 0Zm-.99 5H12a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2");
}

</style>
