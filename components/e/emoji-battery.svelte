<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="pr8znobsp"/><path class="a6t1uccgh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:emoji-battery" {...props}></Icon>
<style>
:global(.a6t1uccgh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.7 18.3h20.954v11.602H8.7z");
}

:global(.pr8znobsp) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.35 20.735v-4.37a.61.61 0 0 0-.612-.61H6.112a.61.61 0 0 0-.612.61v15.27c0 .337.274.61.612.61H38.74a.61.61 0 0 0 .612-.61V27.56H42.5v-6.826z");
}

</style>
