<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="r4h1y5b9l"/><path class="qhmmthblk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:file-code" {...props}></Icon>
<style>
:global(.qhmmthblk) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.26 34.26L13.5 29.5l4.76-4.76m11.48 0l4.76 4.76l-4.76 4.76m-7.927 2.24l4-14");
}

:global(.r4h1y5b9l) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.5 15.5h-9a2 2 0 0 1-2-2v-9h-18a2 2 0 0 0-2 2v35a2 2 0 0 0 2 2h27a2 2 0 0 0 2-2zm-11-11l11 11");
}

</style>
