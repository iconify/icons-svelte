<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xc4__ubpu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:float-portrait-outline-sharp" {...props}></Icon>
<style>
:global(.xc4__ubpu) {
  fill: currentColor;
  d: path("M4 22V2h16v11h-2V4H6v16h7v2Zm11 0v-7h5v7Zm-3-10Z");
}

</style>
