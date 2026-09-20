<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v5kwmfbce"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:reset-tv-outline-sharp" {...props}></Icon>
<style>
:global(.v5kwmfbce) {
  fill: currentColor;
  d: path("M9 20v-2H3V4h18v4.5h-1V5H4v12h16v-5.5h-8.392l2.35 2.35l-.708.708L9.692 11l3.558-3.558l.708.708l-2.35 2.35H21V18h-6v2zm3.5-9");
}

</style>
