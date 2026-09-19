<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="x2xu2umfc"/><circle class="qgie5perq"/><circle class="b-sxirohb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="emojione-monotone:division-sign" {...props}></Icon>
<style>
:global(.b-sxirohb) {
  cx: 32px;
  cy: 54.5px;
  r: 7.5px;
  fill: currentColor;
}

:global(.qgie5perq) {
  cx: 32px;
  cy: 9.5px;
  r: 7.5px;
  fill: currentColor;
}

:global(.x2xu2umfc) {
  fill: currentColor;
  d: path("M2 26h60v12H2z");
}

</style>
