<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><circle class="mc8zfnb7w"/><path class="ksycnbcez"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:letter-lowercase-circle-i" {...props}></Icon>
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

:global(.ksycnbcez) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 21.025v10.6");
}

:global(.mc8zfnb7w) {
  cx: 24px;
  cy: 17.125px;
  r: 0.75px;
  fill: currentColor;
}

</style>
