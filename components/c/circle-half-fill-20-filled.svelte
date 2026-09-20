<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="oep2_1mtc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:circle-half-fill-20-filled" {...props}></Icon>
<style>
:global(.oep2_1mtc) {
  fill: currentColor;
  d: path("M3.5 10a6.5 6.5 0 0 1 13 0zM10 2a8 8 0 1 0 0 16a8 8 0 0 0 0-16");
}

</style>
