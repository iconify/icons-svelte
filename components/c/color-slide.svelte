<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="av-rq91pj"/><path class="jtleoccyh"/><path class="kub116bva"/><path class="a5rjb3bax"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:color-slide" {...props}></Icon>
<style>
:global(.a5rjb3bax) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.917 24H7.834l-4.041 7l4.041 7h8.083l4.042-7zm24.249 0h-8.083l-4.042 7l4.042 7h8.083l4.041-7z");
}

:global(.av-rq91pj) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.041 3h-8.082l-4.042 7l4.042 7h8.082l4.042-7zm0 28h-8.082l-4.042 7l4.042 7h8.082l4.042-7z");
}

:global(.jtleoccyh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.917 10H7.834l-4.041 7l4.041 7h8.083l4.042-7zm24.249 0h-8.083l-4.042 7l4.042 7h8.083l4.041-7z");
}

:global(.kub116bva) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.041 17h-8.082l-4.042 7l4.042 7h8.082l4.042-7z");
}

</style>
