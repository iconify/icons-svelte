<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="jy94fv_4g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:equal-circle-20-filled" {...props}></Icon>
<style>
:global(.jy94fv_4g) {
  fill: currentColor;
  d: path("M10 2a8 8 0 1 1 0 16a8 8 0 0 1 0-16m3.5 7a.5.5 0 0 0 0-1h-7a.5.5 0 0 0 0 1zm0 3a.5.5 0 0 0 0-1h-7a.5.5 0 0 0 0 1z");
}

</style>
