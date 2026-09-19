<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<ellipse transform="rotate(-30.724 11.064 12.074)" class="t39qcobba"/><ellipse transform="rotate(-15.513 27.007 8.83)" class="evc1qhb0j"/><ellipse transform="rotate(-85.227 27.983 30.172)" class="sktu0ynsq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:logseq" {...props}></Icon>
<style>
:global(.evc1qhb0j) {
  cx: 27.007px;
  cy: 8.83px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 6.127px;
  ry: 4.158px;
}

:global(.sktu0ynsq) {
  cx: 27.983px;
  cy: 30.172px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 13.312px;
  ry: 15.347px;
}

:global(.t39qcobba) {
  cx: 11.064px;
  cy: 12.074px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 5.979px;
  ry: 7.403px;
}

</style>
