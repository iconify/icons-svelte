<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="i0xpxnzlv"/><circle class="i5kqru1go"/><circle class="fcp2k0wsl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:labnex" {...props}></Icon>
<style>
:global(.fcp2k0wsl) {
  cx: 30.801px;
  cy: 29.664px;
  r: 1.75px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.i0xpxnzlv) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24 42.5l18.5-14.586L36.312 5.5l-6.136 14.478H17.824L11.688 5.5L5.5 27.914z");
}

:global(.i5kqru1go) {
  cx: 17.199px;
  cy: 29.664px;
  r: 1.75px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
