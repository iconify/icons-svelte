<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="m5k6mccwu"/><path class="e_oya7bvz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:axetfilemanager" {...props}></Icon>
<style>
:global(.e_oya7bvz) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.5 18.28h-39V37a2.18 2.18 0 0 0 2.17 2.2h34.65A2.18 2.18 0 0 0 43.5 37h0Zm-11.33 4.75h5.68m-5.68 5.69h3.69m-3.69-5.69V34.4");
}

:global(.m5k6mccwu) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M41.68 13H24.77c-2-.1-5.93-4.23-8.19-4.23h-9.9A2.18 2.18 0 0 0 4.5 11h0v7.29h39v-3.42A1.83 1.83 0 0 0 41.68 13Z");
}

</style>
