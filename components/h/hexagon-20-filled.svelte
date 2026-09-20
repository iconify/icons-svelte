<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="mxxtshbis"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:hexagon-20-filled" {...props}></Icon>
<style>
:global(.mxxtshbis) {
  fill: currentColor;
  d: path("M6.826 3a1.5 1.5 0 0 0-1.3.75l-3.175 5.5a1.5 1.5 0 0 0 0 1.5l3.176 5.5a1.5 1.5 0 0 0 1.299.75h6.35a1.5 1.5 0 0 0 1.3-.75l3.175-5.5a1.5 1.5 0 0 0 0-1.5l-3.176-5.5A1.5 1.5 0 0 0 13.176 3z");
}

</style>
