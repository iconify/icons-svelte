<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="wv2flf2hg"/><circle class="cj71dkbis"/><circle class="a_xgo4bwr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:nextcloud" {...props}></Icon>
<style>
:global(.a_xgo4bwr) {
  cx: 38.47px;
  cy: 24px;
  r: 5.03px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.cj71dkbis) {
  cx: 9.53px;
  cy: 24px;
  r: 5.03px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.wv2flf2hg) {
  cx: 24px;
  cy: 24px;
  r: 9.44px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
