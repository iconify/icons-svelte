<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="s3qxiu9yy"/><path class="z07byac5f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:bingx" {...props}></Icon>
<style>
:global(.s3qxiu9yy) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.5 36.398c-8.503 0-13.462-4.697-19.5-12.398S13.003 11.602 4.5 11.602");
}

:global(.z07byac5f) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.5 11.602c-8.503 0-13.462 4.697-19.5 12.398S13.003 36.398 4.5 36.398");
}

</style>
