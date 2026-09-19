<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="n9ybnqb2p"/><circle class="t1ivw6btt"/><path class="h4njyd2fl"/><circle class="xfg4ve1-z"/><path class="zf4gchb5p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:remo" {...props}></Icon>
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

:global(.h4njyd2fl) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m7.8 29.6l3.3-5l1.9 2l3.1-5.4l3.2 8.5m8.6-11.5h13.2v11.7H27.9z");
}

:global(.n9ybnqb2p) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 8v32M7 18.2h13.2v11.7H7z");
}

:global(.t1ivw6btt) {
  cx: 10.7px;
  cy: 21.2px;
  r: 1.3px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.xfg4ve1-z) {
  cx: 31.6px;
  cy: 21.2px;
  r: 1.3px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.zf4gchb5p) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m28.7 29.6l3.3-5l1.9 2l3.1-5.4l3.2 8.5");
}

</style>
