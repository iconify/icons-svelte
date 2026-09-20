<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="o-bk3m1fq"/><path class="yex8jvb4w"/><path class="cbebvomry"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:life-fitness" {...props}></Icon>
<style>
:global(.cbebvomry) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.947 6.196L29.75 24L11.947 41.804");
}

:global(.o-bk3m1fq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M3.127 19.127A21.5 21.5 0 0 0 2.5 24a21.5 21.5 0 0 0 .627 4.873L8 24zM24 2.5a21.5 21.5 0 0 0-5.275.725L39.5 24L18.725 44.775a21.5 21.5 0 0 0 5.275.724A21.5 21.5 0 0 0 45.5 24A21.5 21.5 0 0 0 24 2.5");
}

:global(.yex8jvb4w) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.997 12.247L17.75 24L5.997 35.753");
}

</style>
