<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><circle class="regdjobyu"/><circle class="k5zm5ebnd"/><path class="v7sme061k"/><path class="rwt_dhxqs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:public-india" {...props}></Icon>
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

:global(.k5zm5ebnd) {
  cx: 24px;
  cy: 15.884px;
  r: 2.324px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.regdjobyu) {
  cx: 24px;
  cy: 15.884px;
  r: 5.811px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.rwt_dhxqs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.351 35.534s2.618-5.81 4.649-5.81s4.649 5.81 4.649 5.81m-13.946 0c-.872 1.51 2.034 4.53 4.648 0m13.946 0c.872 1.51-2.034 4.53-4.648 0");
}

:global(.v7sme061k) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.703 35.534s5.224-10.46 9.297-10.46s9.297 10.46 9.297 10.46");
}

</style>
