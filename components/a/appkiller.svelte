<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="s042v_9ks"/><circle class="npo2ngaqd"/><circle class="d8q2x-bna"/><circle class="g2tvjdwwj"/><circle class="mh4ydh2sf"/><path class="oy47qrb_d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:appkiller" {...props}></Icon>
<style>
:global(.d8q2x-bna) {
  cx: 36.637px;
  cy: 6.606px;
  r: 0.75px;
  fill: currentColor;
}

:global(.g2tvjdwwj) {
  cx: 41.394px;
  cy: 11.363px;
  r: 0.75px;
  fill: currentColor;
}

:global(.mh4ydh2sf) {
  cx: 44.448px;
  cy: 17.356px;
  r: 0.75px;
  fill: currentColor;
}

:global(.npo2ngaqd) {
  cx: 30.644px;
  cy: 3.552px;
  r: 0.75px;
  fill: currentColor;
}

:global(.oy47qrb_d) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32 16L16 32m0-16l16 16");
}

:global(.s042v_9ks) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M45.5 24A21.5 21.5 0 1 1 24 2.5");
}

</style>
