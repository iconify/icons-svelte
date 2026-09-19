<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xh15btbto"/><path class="ryabz87it"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:outline-add-business" {...props}></Icon>
<style>
:global(.ryabz87it) {
  fill: currentColor;
  d: path("M23 18h-3v-3h-2v3h-3v2h3v3h2v-3h3z");
}

:global(.xh15btbto) {
  fill: currentColor;
  d: path("M2 4h15v2H2zm13 13h2v-3h1v-2l-1-5H2l-1 5v2h1v6h9v-6h4zm-6 1H4v-4h5zm-5.96-6l.6-3h11.72l.6 3z");
}

</style>
