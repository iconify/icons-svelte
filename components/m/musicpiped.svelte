<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="tmz9clp-b"/><circle class="ul_hhpq-q"/><path class="rnk1f6bla"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:musicpiped" {...props}></Icon>
<style>
:global(.rnk1f6bla) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.13 30.86V11.5h5.01");
}

:global(.tmz9clp-b) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 2.5A21.51 21.51 0 0 0 2.5 24A21.51 21.51 0 0 0 24 45.5a21.5 21.5 0 0 0 0-43");
}

:global(.ul_hhpq-q) {
  cx: 21.49px;
  cy: 30.86px;
  r: 5.64px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
