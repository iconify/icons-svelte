<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><g class="y9tr6bcfx"><circle class="pzkm1rb7v"/><path class="kihi0bccx"/><path class="mi1auob3s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:moshidon" {...props}></Icon>
<style>
:global(.cpk0fnbgt) {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.kihi0bccx) {
  d: path("M17.917 26.765v-6.464a5.034 5.034 0 1 0-10.067 0v10.432");
}

:global(.mi1auob3s) {
  d: path("M17.917 20.3a5.034 5.034 0 1 1 10.067 0v10.433");
}

:global(.pzkm1rb7v) {
  cx: 35.157px;
  cy: 25.74px;
  r: 4.993px;
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
