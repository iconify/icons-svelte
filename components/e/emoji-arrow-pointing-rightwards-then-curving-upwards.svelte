<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="c1ms93b4r"/><path class="ayxuultft"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:emoji-arrow-pointing-rightwards-then-curving-upwards" {...props}></Icon>
<style>
:global(.ayxuultft) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.587 5.5v22.069c0 8.246-6.685 14.931-14.932 14.931h-4.2");
}

:global(.c1ms93b4r) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.629 15.458L28.587 5.5l9.958 9.958");
}

</style>
