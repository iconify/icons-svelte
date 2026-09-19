<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><circle class="f_v_dfbgn"/><circle class="bvk48sbfr"/><circle class="l0mg34bqc"/><path class="mdimy_3sv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:mpv" {...props}></Icon>
<style>
:global(.bvk48sbfr) {
  cx: 25.165px;
  cy: 22.721px;
  r: 16.612px;
}

:global(.f_v_dfbgn) {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
}

:global(.l0mg34bqc) {
  cx: 23.139px;
  cy: 24.408px;
  r: 10.762px;
}

:global(.mdimy_3sv) {
  d: path("m20.712 20.011l-.204 8.71l7.36-4.392z");
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
