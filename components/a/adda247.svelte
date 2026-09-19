<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="wv4b38b-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:adda247" {...props}></Icon>
<style>
:global(.wv4b38b-a) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.445 43.451L24.854 4.6l-15.129 39c10.757-6.374 19.775-6.374 29.72-.149");
}

</style>
