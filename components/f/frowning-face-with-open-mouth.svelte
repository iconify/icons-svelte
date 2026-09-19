<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="q9-lck51j"/><path class="czin2bcss"/><g class="mrjy-p0fq"><ellipse class="ksib36f4m"/><ellipse class="jcj9cx5gf"/></g><path class="maelllb8j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="emojione-v1:frowning-face-with-open-mouth" {...props}></Icon>
<style>
:global(.czin2bcss) {
  fill: var(--svg-color--fff, #fff);
  d: path("M27.365 23.17c0 5.38-2.907 9.733-6.498 9.733c-3.594 0-6.501-4.353-6.501-9.733c0-5.375 2.907-9.732 6.501-9.732c3.591 0 6.498 4.357 6.498 9.732m21.995 0c0 5.38-2.907 9.733-6.498 9.733c-3.59 0-6.501-4.353-6.501-9.733c0-5.375 2.911-9.732 6.501-9.732s6.498 4.357 6.498 9.732");
}

:global(.jcj9cx5gf) {
  cx: 42.857px;
  cy: 23.17px;
  rx: 4.207px;
  ry: 5.1px;
}

:global(.ksib36f4m) {
  cx: 20.865px;
  cy: 23.17px;
  rx: 4.205px;
  ry: 5.1px;
}

:global(.maelllb8j) {
  fill: var(--svg-color--633d19, #633d19);
  d: path("M48.2 47.538c0 6.257-6.556 4.116-15.496 4.116s-16.882 2.141-16.882-4.116S23.07 36.21 32.011 36.21c8.943 0 16.189 5.071 16.189 11.328");
}

:global(.mrjy-p0fq) {
  fill: var(--svg-color--25333a, #25333a);
}

:global(.q9-lck51j) {
  fill: var(--svg-color--fbbf67, #fbbf67);
  d: path("M63.957 31.979c0 17.66-14.318 31.979-31.982 31.979S0 49.64 0 31.979C0 14.315 14.311 0 31.975 0s31.982 14.315 31.982 31.979");
}

</style>
