<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="svhn43alt"/><circle class="ui1zimbxa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:a-color-story" {...props}></Icon>
<style>
:global(.cpk0fnbgt) {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.svhn43alt) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24 23.943l8.206-19.811M24 23.943l19.811-8.206M24 23.943l19.811 8.206M24 23.943l8.206 19.811M24 23.943l-8.206 19.811M24 23.943L4.189 32.149M24 23.943L4.189 15.737M24 23.943L15.794 4.132");
}

:global(.ui1zimbxa) {
  cx: 24px;
  cy: 24px;
  r: 10.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
