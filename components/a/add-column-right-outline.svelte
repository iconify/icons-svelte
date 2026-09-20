<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ug2grlb9b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:add-column-right-outline" {...props}></Icon>
<style>
:global(.ug2grlb9b) {
  fill: currentColor;
  d: path("M4 5v14h6.558V5zM3 20V4h16v3.116h-1V5h-6.442v14H18v-2.116h1V20zm7.558-8h1zM18 14.5v-2h-2v-1h2v-2h1v2h2v1h-2v2z");
}

</style>
