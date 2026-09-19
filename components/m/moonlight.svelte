<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><circle class="wkxw5hbfm"/><path class="nzz_b4b9i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:moonlight" {...props}></Icon>
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

:global(.nzz_b4b9i) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 2.5V21m0 6v18.5M45.5 24H27m-6 0H2.5M39.2 8.8L26.12 21.88m-4.24 4.24L8.8 39.2m30.4 0L26.12 26.12m-4.24-4.24L8.8 8.8");
}

:global(.wkxw5hbfm) {
  cx: 24px;
  cy: 24px;
  r: 3px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
