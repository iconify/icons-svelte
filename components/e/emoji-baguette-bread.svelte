<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="l6ytns8jz"/><path class="zm8n1wvit"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:emoji-baguette-bread" {...props}></Icon>
<style>
:global(.l6ytns8jz) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M7.508 30.804a6.853 6.853 0 0 0 9.69 9.69l23.295-23.297a6.853 6.853 0 0 0-9.69-9.69z");
}

:global(.zm8n1wvit) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.803 7.507a6.853 6.853 0 0 0 0 9.69m-5.824-3.867a6.853 6.853 0 0 0 0 9.691m-5.824-3.866a6.854 6.854 0 0 0 0 9.69m-5.823-3.865a6.853 6.853 0 0 0 0 9.69");
}

</style>
