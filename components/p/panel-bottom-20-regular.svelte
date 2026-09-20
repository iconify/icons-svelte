<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="odfwswbge"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:panel-bottom-20-regular" {...props}></Icon>
<style>
:global(.odfwswbge) {
  fill: currentColor;
  d: path("M5 3a3 3 0 0 0-3 3v7a3 3 0 0 0 3 3h10a3 3 0 0 0 3-3V6a3 3 0 0 0-3-3zM3 6a2 2 0 0 1 2-2h10a2 2 0 0 1 2 2v5H3zm0 6h14v1a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2z");
}

</style>
