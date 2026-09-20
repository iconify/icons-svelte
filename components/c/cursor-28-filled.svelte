<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":28,"height":28};
const content = `<path class="gp304300s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:cursor-28-filled" {...props}></Icon>
<style>
:global(.gp304300s) {
  fill: currentColor;
  d: path("M6 3.604c0-1.346 1.56-2.09 2.607-1.243l16.88 13.669c1.018.824.435 2.47-.875 2.47h-9.377a2.25 2.25 0 0 0-1.749.835l-4.962 6.134C7.682 26.51 6 25.915 6 24.576z");
}

</style>
