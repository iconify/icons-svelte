<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ur-aie38z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:everywiki" {...props}></Icon>
<style>
:global(.ur-aie38z) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4m-19.75 8v21m-3.231 0h16.962m-16.962-21h16.962M18.75 24h10.077m0 1.615v-3.23m3.654-5.654V13.5m0 21v-3.231");
}

</style>
