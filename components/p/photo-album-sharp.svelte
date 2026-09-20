<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t04xfgbap"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:photo-album-sharp" {...props}></Icon>
<style>
:global(.t04xfgbap) {
  fill: currentColor;
  d: path("M4 22V2h16v20zm3-4h10l-3.375-4.5L11 17l-1.625-2.175zm4-7l2.5-1.5L16 11V4h-5z");
}

</style>
