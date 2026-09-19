<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="zxk2hj71d"/><path class="jbp86e2gc"/></g><circle class="cpk0fnbgt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:kideapp" {...props}></Icon>
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

:global(.jbp86e2gc) {
  d: path("m19.578 29.232l8.605 9.99h3.256v-3.135l-7.903-8.483");
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.zxk2hj71d) {
  d: path("m16.574 12.06l2.378-3.282l2.4 3.282v11.544l6.817-6.779h3.04v3.149l-8.46 8.413l-3.17.845l-3.018-3z");
}

</style>
