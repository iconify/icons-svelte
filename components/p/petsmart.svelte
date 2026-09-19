<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="dmgs-kxhw"/><circle class="o_vmdgbuq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:petsmart" {...props}></Icon>
<style>
:global(.dmgs-kxhw) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.5 21.317c11.398-3.936 17.941-1.125 22.592 6.133m1.789 2.914c1.943-5.98 5.93-6.872 5.93-6.872");
}

:global(.o_vmdgbuq) {
  cx: 39.922px;
  cy: 21.214px;
  r: 3.578px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
