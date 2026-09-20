<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gveijgajs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:power-plug-outline-sharp" {...props}></Icon>
<style>
:global(.gveijgajs) {
  fill: currentColor;
  d: path("M11.5 19h1v-1.85l3.5-3.5V9H8v4.65l3.5 3.5zm-2 2v-3L6 14.5V7h2V3h2v4h4V3h2v4h2v7.5L14.5 18v3zm2.5-7");
}

</style>
