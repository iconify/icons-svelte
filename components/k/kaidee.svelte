<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="qxv9c4b7w"/><circle class="dmqxq9l9v"/><path class="hmj5cxbqt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:kaidee" {...props}></Icon>
<style>
:global(.dmqxq9l9v) {
  cx: 20.754px;
  cy: 20.077px;
  r: 0.75px;
  fill: currentColor;
}

:global(.hmj5cxbqt) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.754 22.456v5.147m-2.069-1.943c0 1.074-.87 1.943-1.942 1.943h0a1.94 1.94 0 0 1-1.943-1.942v-1.263c0-1.072.87-1.942 1.942-1.942h0c1.073 0 1.943.87 1.943 1.942m0 3.205v-5.147m13.679 4.167c-.335.586-.965.98-1.688.98h0a1.94 1.94 0 0 1-1.942-1.942v-1.263c0-1.072.87-1.942 1.942-1.942h0c1.073 0 1.942.87 1.942 1.942v.632h-3.884m9.511 1.593a1.94 1.94 0 0 1-1.687.98h0a1.94 1.94 0 0 1-1.943-1.942v-1.263c0-1.072.87-1.942 1.943-1.942h0c1.072 0 1.942.87 1.942 1.942v.632h-3.885m-7.865-.632c0-1.072-.87-1.942-1.942-1.942h0c-1.073 0-1.943.87-1.943 1.942v1.263c0 1.072.87 1.942 1.943 1.942h0c1.072 0 1.942-.87 1.942-1.942m0 1.942v-7.769");
}

:global(.j3s9ivbxi) {
  width: 37px;
  height: 37px;
  x: 5.5px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

:global(.qxv9c4b7w) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.5 19.834v7.769m.001-1.65l3.517-3.5m-2.398 2.386l2.765 2.753");
}

</style>
