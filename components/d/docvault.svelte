<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="kg4ghsblu"/><g class="y9tr6bcfx"><circle class="yoe7t2mag"/><path class="u8koz3bib"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:docvault" {...props}></Icon>
<style>
:global(.kg4ghsblu) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 43.5c9.043-3.117 15.489-10.363 16.5-19.589c.28-4.005.257-8.025-.071-12.027a2.54 2.54 0 0 0-2.468-2.366c-4.091-.126-8.846-.808-12.52-4.427a2.05 2.05 0 0 0-2.881 0c-3.675 3.619-8.43 4.301-12.52 4.427a2.54 2.54 0 0 0-2.468 2.366A79.4 79.4 0 0 0 7.5 23.911C8.512 33.137 14.957 40.383 24 43.5");
}

:global(.u8koz3bib) {
  d: path("M24 28.262v-3.608");
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.yoe7t2mag) {
  cx: 24px;
  cy: 21.196px;
  r: 3.458px;
}

</style>
