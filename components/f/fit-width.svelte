<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fnpnvqr1y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:fit-width" {...props}></Icon>
<style>
:global(.fnpnvqr1y) {
  fill: currentColor;
  d: path("M3 21V3h2v18zm16 0V3h2v18zM7 13v-2h2v2zm4 0v-2h2v2zm4 0v-2h2v2z");
}

</style>
