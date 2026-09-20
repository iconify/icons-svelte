<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><g class="y9tr6bcfx"><path class="buv34eb2m"/><path class="byrm-_b_v"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:agora" {...props}></Icon>
<style>
:global(.buv34eb2m) {
  d: path("M15.184 24.65a2 2 0 1 1-4 0v-1.3a2 2 0 1 1 4 0m0 3.3v-5.3m6.047 0v6a2 2 0 0 1-2 2a2 2 0 0 1-1.414-.586");
}

:global(.byrm-_b_v) {
  d: path("M19.231 26.65za2 2 0 0 1-2-2v-1.3a2 2 0 1 1 4 0v1.3a2 2 0 0 1-2 2m6.047-5.3za2 2 0 0 1 2 2v1.3a2 2 0 1 1-4 0v-1.3a2 2 0 0 1 2-2m4.046 2a2 2 0 0 1 2-2m-2 0v5.3m7.492-2a2 2 0 1 1-4 0v-1.3a2 2 0 1 1 4 0m0 3.3v-5.3");
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

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
