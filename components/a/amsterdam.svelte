<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="oq_jbbcmp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:amsterdam" {...props}></Icon>
<style>
:global(.oq_jbbcmp) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m19.277 3.5l9.446 9.445m-9.446 0L28.723 3.5m-9.446 15.777l9.446 9.446m-9.446 0l9.446-9.446m-9.446 15.778l9.446 9.445m-9.446 0l9.446-9.445");
}

</style>
