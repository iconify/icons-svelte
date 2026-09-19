<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="sajw_rsvl"/><circle class="hr7if4b7f"/><circle class="jl3vzcb8c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:morele-net" {...props}></Icon>
<style>
:global(.hr7if4b7f) {
  cx: 10px;
  cy: 24px;
  r: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.jl3vzcb8c) {
  cx: 40px;
  cy: 24px;
  r: 3.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.sajw_rsvl) {
  cx: 26px;
  cy: 24px;
  r: 10.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
