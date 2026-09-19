<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="nofj9bctb"/><ellipse class="a2hmc2mea"/><ellipse transform="rotate(-30 24 24)" class="s5g5uachw"/><ellipse transform="rotate(-60 24 24)" class="a2hmc2mea"/><path class="d0exevcyq"/><circle class="umrgg09or"/><path class="vkr_0ncwz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:atom" {...props}></Icon>
<style>
:global(.a2hmc2mea) {
  cx: 24px;
  cy: 24px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 6.85px;
  ry: 16.337px;
}

:global(.d0exevcyq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M40.338 24v20.14");
}

:global(.nofj9bctb) {
  cx: 24px;
  cy: 24px;
  r: 16.337px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.s5g5uachw) {
  cx: 24px;
  cy: 24px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 16.337px;
  ry: 6.85px;
}

:global(.umrgg09or) {
  cx: 24px;
  cy: 24px;
  r: 2.868px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.vkr_0ncwz) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37.183 40.985A21.5 21.5 0 1 1 45.5 24v18.44");
}

</style>
