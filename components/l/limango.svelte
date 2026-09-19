<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="e8_j36bcm"/><circle class="v184tjueq"/><circle class="remkdlbvl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:limango" {...props}></Icon>
<style>
:global(.e8_j36bcm) {
  cx: 23.25px;
  cy: 9px;
  r: 4.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.remkdlbvl) {
  cx: 20.25px;
  cy: 33.5px;
  r: 10px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.v184tjueq) {
  cx: 29.75px;
  cy: 26.5px;
  r: 8px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
