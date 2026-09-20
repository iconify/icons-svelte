<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d59z-7-at"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:difference-outline-sharp" {...props}></Icon>
<style>
:global(.d59z-7-at) {
  fill: currentColor;
  d: path("M13 10.5h1v-2h2v-1h-2v-2h-1v2h-2v1h2zm-2 4h5v-1h-5zM7 18V2h8.5L20 6.5V18zm1-1h11V7l-4-4H8zm-5 5V8h1v13h10v1zm5-5V3z");
}

</style>
