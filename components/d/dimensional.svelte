<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><circle class="dfcdh9g5e"/><path class="rdnad88be"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:dimensional" {...props}></Icon>
<style>
:global(.dfcdh9g5e) {
  cx: 8.498px;
  cy: 24px;
  r: 4.998px;
}

:global(.rdnad88be) {
  d: path("M19.154 19.269v9.462m4.464-9.462v9.462m4.462-9.462v9.462m16.42-.069H33.733l5.383-9.503z");
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
