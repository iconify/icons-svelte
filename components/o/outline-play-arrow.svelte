<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w-5e-6bny"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:outline-play-arrow" {...props}></Icon>
<style>
:global(.w-5e-6bny) {
  fill: currentColor;
  d: path("M10 8.64L15.27 12L10 15.36zM8 5v14l11-7z");
}

</style>
