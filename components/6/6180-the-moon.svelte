<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="yq5wxkb5w"/><circle class="rksbom0mx"/><path class="bu7x0vb2e"/><rect class="ckyboq04o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:6180-the-moon" {...props}></Icon>
<style>
:global(.bu7x0vb2e) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.358 20.446c-.51-.669-1.289-1.129-2.578-1.129h-.215a3.065 3.065 0 0 0-3.065 3.065v3.122m14.859-1.447a2.313 2.313 0 1 0 0 4.626h1.503a2.313 2.313 0 1 0 0-4.626m0 0a2.313 2.313 0 1 0 0-4.626H25.36a2.313 2.313 0 1 0 0 4.626m-.001 0h1.503");
}

:global(.ckyboq04o) {
  width: 6.129px;
  height: 9.252px;
  x: 31.371px;
  y: 19.317px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 3.065px;
  ry: 3.065px;
}

:global(.cpk0fnbgt) {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.rksbom0mx) {
  cx: 13.565px;
  cy: 25.505px;
  r: 3.065px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.yq5wxkb5w) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m18.537 20.577l2.313-1.26v9.252");
}

</style>
