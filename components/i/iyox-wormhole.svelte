<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="s-66xkinn"/><circle class="yrrh7b4gn"/><circle class="v5ejp6bjl"/><circle class="d4m6sm-2m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:iyox-wormhole" {...props}></Icon>
<style>
:global(.d4m6sm-2m) {
  cx: 21.944px;
  cy: 26.056px;
  r: 8.222px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.s-66xkinn) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.553 12.558A16.44 16.44 0 0 1 26.056 5.5c9.082 0 16.444 7.362 16.444 16.444h0c0 5.385-2.636 10.43-7.058 13.503");
}

:global(.v5ejp6bjl) {
  cx: 21.944px;
  cy: 26.056px;
  r: 12.333px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.yrrh7b4gn) {
  cx: 21.944px;
  cy: 26.056px;
  r: 16.444px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
