<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="x9dmvpbsy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:measure" {...props}></Icon>
<style>
:global(.x9dmvpbsy) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.263 17.871v12.48L20.212 43.5L9.737 37.26L27.12 24.111L9.737 10.74L20.211 4.5zl-11.143 6.24l11.143 6.24");
}

</style>
