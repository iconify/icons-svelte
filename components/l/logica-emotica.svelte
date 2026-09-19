<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><circle class="f_v_dfbgn"/><circle class="zvasn3b7g"/><ellipse class="ee4-zabbw"/><path class="l55blfb_l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:logica-emotica" {...props}></Icon>
<style>
:global(.ee4-zabbw) {
  cx: 15.632px;
  cy: 21.007px;
  rx: 2.932px;
  ry: 4.52px;
}

:global(.f_v_dfbgn) {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
}

:global(.l55blfb_l) {
  d: path("M29.436 21.007c0 2.496 1.313 4.52 2.932 4.52s2.932-2.024 2.932-4.52s-1.313-4.52-2.932-4.52s-2.932 2.024-2.932 4.52m-18.873-7.696s4.397-3.97 9.711-2.199m17.164 2.199s-4.398-3.97-9.712-2.199");
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.zvasn3b7g) {
  cx: 24px;
  cy: 35.055px;
  r: 3.482px;
}

</style>
