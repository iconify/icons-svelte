<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ohrpceb7h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:nowplaying4droid" {...props}></Icon>
<style>
:global(.ohrpceb7h) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.916 5.5v30.4m4.8-16.2h-16.2m16.2 7.6h-16.2m3.8-15.2v30.4m25.169-10.679l-9.766-8.189V40.01z");
}

</style>
