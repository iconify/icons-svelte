<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="vitkjnb7x"/><circle class="e4sq83bws"/><circle class="f7wqasbkf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:moto-tag" {...props}></Icon>
<style>
:global(.e4sq83bws) {
  cx: 24px;
  cy: 24px;
  r: 15px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.f7wqasbkf) {
  cx: 24px;
  cy: 24px;
  r: 9px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.vitkjnb7x) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.565 3.233a21.5 21.5 0 0 1 15.203 15.203M18.435 44.767A21.5 21.5 0 0 1 3.232 29.564");
}

</style>
