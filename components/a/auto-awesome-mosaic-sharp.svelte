<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z8b3xebcf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:auto-awesome-mosaic-sharp" {...props}></Icon>
<style>
:global(.z8b3xebcf) {
  fill: currentColor;
  d: path("M11 20H4V4h7zm2-9V4h7v7zm0 9v-7h7v7z");
}

</style>
