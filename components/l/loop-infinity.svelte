<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ln5rwnb5y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:loop-infinity" {...props}></Icon>
<style>
:global(.ln5rwnb5y) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m20.269 28.202l-1.517 1.709a8.352 8.352 0 1 1 0-11.822l10.496 11.822a8.352 8.352 0 1 0 0-11.822l-1.517 1.709");
}

</style>
