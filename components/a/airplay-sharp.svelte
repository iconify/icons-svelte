<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="otgwc7mka"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:airplay-sharp" {...props}></Icon>
<style>
:global(.otgwc7mka) {
  fill: currentColor;
  d: path("m6 21l6-6l6 6zm-4-2V3h20v16h-3l-7-7l-7 7z");
}

</style>
