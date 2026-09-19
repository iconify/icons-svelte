<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="timfdq6ad"/><circle class="g8hsl5phr"/><path class="efl66ebig"/><circle class="siz3z5r5d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:camo" {...props}></Icon>
<style>
:global(.efl66ebig) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.21 26.77L10.74 43.5h26.22L24.908 26.749");
}

:global(.g8hsl5phr) {
  cx: 24px;
  cy: 21.931px;
  r: 4.903px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.siz3z5r5d) {
  cx: 24px;
  cy: 22.103px;
  r: 8.432px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.timfdq6ad) {
  cx: 24px;
  cy: 21.931px;
  r: 17.433px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
