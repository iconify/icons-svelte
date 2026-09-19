<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="junbpjbvj"/><circle class="ob80bkxjz"/><circle class="bfdxdbbtw"/><circle class="pc18swb5w"/><circle class="obt57xbxv"/><circle class="z9k0rgbca"/><circle class="wyfkqq0dg"/><path class="yt6u_3b0r"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:arcticonsdark" {...props}></Icon>
<style>
:global(.bfdxdbbtw) {
  cx: 24px;
  cy: 5.6px;
  r: 3.1px;
}

:global(.junbpjbvj) {
  d: path("m24 10.8l-11.4 6.6v13.2L24 37.2l11.4-6.6V17.4L24 10.8z");
}

:global(.ob80bkxjz) {
  cx: 8.1px;
  cy: 14.8px;
  r: 3.1px;
}

:global(.obt57xbxv) {
  cx: 39.9px;
  cy: 33.2px;
  r: 3.1px;
}

:global(.pc18swb5w) {
  cx: 39.9px;
  cy: 14.8px;
  r: 3.1px;
}

:global(.wyfkqq0dg) {
  cx: 8.1px;
  cy: 33.2px;
  r: 3.1px;
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.yt6u_3b0r) {
  d: path("m12.6 30.6l-1.8 1M24 37.2v2.1m0-28.5V8.7m11.4 21.9l1.8 1m-1.8-14.2l1.8-1m-24.6 1l-1.8-1m10.6 13.1v-11h2.5c2.7 0 4.8 2.2 4.8 4.8c0 0 0 0 0 0v1.4c0 2.7-2.2 4.8-4.8 4.8c0 0 0 0 0 0h-2.5z");
}

:global(.z9k0rgbca) {
  cx: 24px;
  cy: 42.4px;
  r: 3.1px;
}

</style>
