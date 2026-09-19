<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="dd2tyqbmj"/><path class="x15-jszue"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:certilia" {...props}></Icon>
<style>
:global(.dd2tyqbmj) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.383 24c0-11.787 12.557-19.5 21.705-19.5c2.395 0 4.974.57 7.529 1.458l-5.376 9.006c-6.1-.18-19.552-1.48-23.857 9.036Zm0 0c0 11.787 12.557 19.5 21.705 19.5c2.395 0 4.974-.57 7.529-1.458c0 0-15.421-3.938-19.906-18.042z");
}

:global(.x15-jszue) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 14.985L18.711 24H9.383");
}

</style>
