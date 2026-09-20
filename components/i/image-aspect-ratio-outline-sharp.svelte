<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aq2co8zdg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:image-aspect-ratio-outline-sharp" {...props}></Icon>
<style>
:global(.aq2co8zdg) {
  fill: currentColor;
  d: path("M6 12h2v-2H6zm4 0h2v-2h-2zm4 4h2v-2h-2zm0-4h2v-2h-2zM2 20V4h20v16zm2-2h16V6H4zm0 0V6z");
}

</style>
