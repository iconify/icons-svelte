<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gjgx2qbcs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:laptop-fill-round" {...props}></Icon>
<style>
:global(.gjgx2qbcs) {
  fill: currentColor;
  d: path("M4 15.171V8a5 5 0 0 1 5-5h6a5 5 0 0 1 5 5v7.171A3.001 3.001 0 0 1 19 21H5a3 3 0 0 1-1-5.829M5 17a1 1 0 0 0 0 2h14a1 1 0 0 0 0-2Z");
}

</style>
