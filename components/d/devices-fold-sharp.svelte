<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s44sldphn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:devices-fold-sharp" {...props}></Icon>
<style>
:global(.s44sldphn) {
  fill: currentColor;
  d: path("M10 21V2.975l7-3.05V3h5v18zm4.675-2H20V5h-3v13.025zM2 5V3h2v2zm0 16v-2h2v2zm0-4v-2h2v2zm0-4v-2h2v2zm0-4V7h2v2zm4-4V3h2v2zm0 16v-2h2v2z");
}

</style>
