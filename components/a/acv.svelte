<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="zno-oj5gh"/><ellipse class="un7sl2bpn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:acv" {...props}></Icon>
<style>
:global(.un7sl2bpn) {
  cx: 24px;
  cy: 22.061px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 18.5px;
  ry: 16.312px;
}

:global(.zno-oj5gh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.253 35.985c-.299.796-.597 1.79-1.194 2.885a14.2 14.2 0 0 1-2.486 3.381c1.193-.199 2.984-.596 4.873-1.591c1.79-.895 3.084-1.99 3.979-2.785m13.029-1.392v-8.554m-25.363.398l34.017-.597M14.054 8.434v8.753m-7.957.895l34.414-3.083");
}

</style>
