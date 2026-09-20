<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="rj67htlvw"/><circle class="h4p5wibrl"/><circle class="hdjec5b8q"/><circle class="p63_qslps"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="twemoji:horizontal-traffic-light" {...props}></Icon>
<style>
:global(.h4p5wibrl) {
  cx: 7px;
  cy: 18px;
  r: 4px;
  fill: var(--svg-color--77b255, #77b255);
}

:global(.hdjec5b8q) {
  cx: 18px;
  cy: 18px;
  r: 4px;
  fill: var(--svg-color--ffcc4d, #ffcc4d);
}

:global(.p63_qslps) {
  cx: 29px;
  cy: 18px;
  r: 4px;
  fill: var(--svg-color--dd2e44, #dd2e44);
}

:global(.rj67htlvw) {
  fill: var(--svg-color--31373d, #31373d);
  d: path("M36 23a4 4 0 0 1-4 4H4a4 4 0 0 1-4-4V13a4 4 0 0 1 4-4h28a4 4 0 0 1 4 4z");
}

</style>
