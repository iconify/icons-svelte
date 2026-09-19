<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="h0qgeuwow"/><g class="y9tr6bcfx"><circle class="d4vgczbvw"/><circle class="w3arqccjs"/><path class="m-9m380np"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:folder-secure" {...props}></Icon>
<style>
:global(.d4vgczbvw) {
  cx: 24px;
  cy: 26.5px;
  r: 7px;
}

:global(.h0qgeuwow) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.5 11.5a3 3 0 0 1 3-3h8.718a4 4 0 0 1 2.325.745l4.914 3.51a4 4 0 0 0 2.325.745H40.5a3 3 0 0 1 3 3v20a3 3 0 0 1-3 3h-33a3 3 0 0 1-3-3z");
}

:global(.m-9m380np) {
  d: path("M24 27.854v2.292");
}

:global(.w3arqccjs) {
  cx: 24px;
  cy: 25.354px;
  r: 2.5px;
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
