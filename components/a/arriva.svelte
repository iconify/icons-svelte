<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<ellipse transform="rotate(-60.255 17.699 24.864)" class="md2n_-0un"/><ellipse transform="rotate(-28.03 29.346 24)" class="id_xqob9r"/><ellipse transform="rotate(-77.427 24.52 26.263)" class="mt_rwxbjg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:arriva" {...props}></Icon>
<style>
:global(.id_xqob9r) {
  cx: 29.346px;
  cy: 24px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 3.811px;
  ry: 20.858px;
}

:global(.md2n_-0un) {
  cx: 17.699px;
  cy: 24.863px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 19.021px;
  ry: 4.131px;
}

:global(.mt_rwxbjg) {
  cx: 24.521px;
  cy: 26.263px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 3.784px;
  ry: 16.247px;
}

</style>
