<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<ellipse class="nypdm9eoi"/><path class="ekjgikvcl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:oeni" {...props}></Icon>
<style>
:global(.ekjgikvcl) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M6.693 21.45c19.79 9.406 31.513 1.24 33.548.558c7.056-2.363-2.072 20.958-16.206 20.49C5.311 41.877 4.116 20.226 6.693 21.45");
}

:global(.nypdm9eoi) {
  cx: 24.035px;
  cy: 14.107px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 17.343px;
  ry: 7.345px;
}

</style>
