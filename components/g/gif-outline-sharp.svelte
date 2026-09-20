<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uc9ysrlav"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:gif-outline-sharp" {...props}></Icon>
<style>
:global(.uc9ysrlav) {
  fill: currentColor;
  d: path("M11.5 15V9H13v6zM5 15V9h5v1.5H6.5v3h2V12H10v3zm9.5 0V9H19v1.5h-3v1h2V13h-2v2z");
}

</style>
