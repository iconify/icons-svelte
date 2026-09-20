<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e66204dyf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:airplay-outline-sharp" {...props}></Icon>
<style>
:global(.e66204dyf) {
  fill: currentColor;
  d: path("m6 21l6-6l6 6zm-4-2V3h20v16h-5v-2h3V5H4v12h3v2zm10-7");
}

</style>
