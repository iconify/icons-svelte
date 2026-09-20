<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u2vmljbko"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:ink-eraser-sharp" {...props}></Icon>
<style>
:global(.u2vmljbko) {
  fill: currentColor;
  d: path("M17.25 18H22v2h-6.75zm-12.5 2L1.2 16.45L15 2.15l7.8 7.8L13 20z");
}

</style>
