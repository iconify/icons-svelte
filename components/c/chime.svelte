<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="iz7lo-wma"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:chime" {...props}></Icon>
<style>
:global(.iz7lo-wma) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M41.423 29.693c-3.628 3.954-10.702 5.505-10.702 5.505a11.337 11.337 0 1 1 .48-22.078a29.2 29.2 0 0 0 10.249 1.732V6.191s-3.6.452-11.428-1.288A19.503 19.503 0 1 0 26.05 43.5c1.333 0 6.566.119 15.328-4.689Z");
}

</style>
