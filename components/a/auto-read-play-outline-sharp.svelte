<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gx6uv7b0h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:auto-read-play-outline-sharp" {...props}></Icon>
<style>
:global(.gx6uv7b0h) {
  fill: currentColor;
  d: path("M10 13.077L14.616 10L10 6.923zm-7 7V3h18v14H6.077zM5.65 16H20V4H4v13.644zM4 16V4z");
}

</style>
