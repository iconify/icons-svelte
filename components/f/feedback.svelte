<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="mi6x78k3j"/><circle class="suyych5yn"/><path class="fpo06rukq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:feedback" {...props}></Icon>
<style>
:global(.fpo06rukq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.23 19.71a6.77 6.77 0 1 1 13.54 0a6.08 6.08 0 0 1-2 4.79c-1.4 1.12-4.81 3-4.81 5.83v.81");
}

:global(.mi6x78k3j) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.5 43.5h23a4 4 0 0 0 4-4v-31a4 4 0 0 0-4-4h-23a4 4 0 0 0-4 4v31a4 4 0 0 0 4 4");
}

:global(.suyych5yn) {
  cx: 24px;
  cy: 34.66px;
  r: 0.75px;
  fill: currentColor;
}

</style>
