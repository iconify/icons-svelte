<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ygalvrb-n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:crystal-para-samsung-internet" {...props}></Icon>
<style>
:global(.ygalvrb-n) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.75 14.25L24 4.5l-9.75 9.75v19.5L24 43.5l9.75-9.75z");
}

</style>
