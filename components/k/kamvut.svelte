<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="but1twbmq"/><circle class="rq7ktlboa"/><circle class="tmqmg9cny"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:kamvut" {...props}></Icon>
<style>
:global(.but1twbmq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 10.403a37 37 0 0 1 37 0L24 42.554z");
}

:global(.rq7ktlboa) {
  cx: 18.259px;
  cy: 12.954px;
  r: 3.828px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.tmqmg9cny) {
  cx: 24px;
  cy: 24.054px;
  r: 3.828px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
