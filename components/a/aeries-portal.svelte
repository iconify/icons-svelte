<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="udl7ntnvw"/><path class="esm1xodsh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:aeries-portal" {...props}></Icon>
<style>
:global(.esm1xodsh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m36.14 42.5l-1.843-5.635h0h-15.52L16.88 42.5m9.774-29.515L21.163 29.58h10.808z");
}

:global(.udl7ntnvw) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.5 5.5h29a4 4 0 0 1 4 4v29a4 4 0 0 1-4 4h-29a4 4 0 0 1-4-4v-29a4 4 0 0 1 4-4m-1.582 37l13.064-37m11.526 0L42.5 33.767");
}

</style>
