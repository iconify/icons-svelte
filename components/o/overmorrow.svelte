<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<ellipse class="ig-g7ob7w"/><ellipse class="t5ks33bly"/><ellipse class="zb_1zv2qa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:overmorrow" {...props}></Icon>
<style>
:global(.ig-g7ob7w) {
  cx: 16.524px;
  cy: 25.237px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 12.024px;
  ry: 12.045px;
}

:global(.t5ks33bly) {
  cx: 36.886px;
  cy: 17.343px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 6.614px;
  ry: 6.625px;
}

:global(.zb_1zv2qa) {
  cx: 28.735px;
  cy: 30.115px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 6.914px;
  ry: 6.926px;
}

</style>
