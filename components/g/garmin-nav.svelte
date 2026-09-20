<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="s15gkwbmm"/><circle class="c8c-a65gx"/><path class="v06s3vbcl"/><path class="xjlbl_7mo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:garmin-nav" {...props}></Icon>
<style>
:global(.c8c-a65gx) {
  cx: 9.5px;
  cy: 9.433px;
  r: 7px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.s15gkwbmm) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 15.176V38.5a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4H15.291");
}

:global(.v06s3vbcl) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.176 8.115a2.68 2.68 0 0 0-2.82-2.678a2.78 2.78 0 0 0-2.532 2.83v2.485a2.68 2.68 0 0 0 2.676 2.68a2.68 2.68 0 0 0 2.676-2.68s-2.676 0-2.676 0M20.25 35.5v-7.108c0-2.812 1.117-5.509 3.105-7.497L31.75 12.5");
}

:global(.xjlbl_7mo) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.837 12.5h7.913v7.913");
}

</style>
