<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xx69kabod"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:playlist-play-outline-sharp" {...props}></Icon>
<style>
:global(.xx69kabod) {
  fill: currentColor;
  d: path("M3 16v-2h8v2zm0-4v-2h12v2zm0-4V6h12v2zm13 13v-8l6 4z");
}

</style>
