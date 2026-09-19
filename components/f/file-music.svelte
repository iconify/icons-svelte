<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="r4h1y5b9l"/><g class="y9tr6bcfx"><circle class="o-hnrxbuc"/><path class="yqftufwxb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:file-music" {...props}></Icon>
<style>
:global(.o-hnrxbuc) {
  cx: 21.242px;
  cy: 35.096px;
  r: 3.109px;
}

:global(.r4h1y5b9l) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.5 15.5h-9a2 2 0 0 1-2-2v-9h-18a2 2 0 0 0-2 2v35a2 2 0 0 0 2 2h27a2 2 0 0 0 2-2zm-11-11l11 11");
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.yqftufwxb) {
  d: path("M24.352 20.794h5.515v3.743h-5.515zm0 3.743v10.559");
}

</style>
