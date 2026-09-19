<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="vbeb4mbcw"/><path class="agmd98bqe"/><path class="zjsqv7bbp"/><rect class="skqdqyslg"/><path class="gs9b_zkzr"/><path class="pv5v9bb8y"/><path class="agch88bkm"/><path class="omi95fb1j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:japanese-vaccination-certificate" {...props}></Icon>
<style>
:global(.agch88bkm) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.125 20.786h4.109v4.109h-4.109zm9.245 15.317h2.968v2.968H25.37zm2.967-3.109h2.968v2.968h-2.968zm2.968 3.109h2.968v2.968h-2.968z");
}

:global(.agmd98bqe) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.125 32.428h4.109v4.109h-4.109zm9.245-14.039h8.903v8.903H25.37z");
}

:global(.gs9b_zkzr) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.431 7.643h-5.52V43.5h30.177V7.643H33.81v2.659c0 2.179-1.108 3.223-2.7 3.223H17.253c-1.685 0-2.82-.667-2.82-2.82Z");
}

:global(.omi95fb1j) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.37 30.168h2.968v2.968H25.37zm5.935 0h2.968v2.968h-2.968z");
}

:global(.pv5v9bb8y) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.728 18.389h8.903v8.903h-8.903z");
}

:global(.skqdqyslg) {
  width: 13.457px;
  height: 6.084px;
  x: 17.453px;
  y: 4.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.064px;
}

:global(.vbeb4mbcw) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.728 30.031h8.903v8.903h-8.903z");
}

:global(.zjsqv7bbp) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.767 20.786h4.109v4.109h-4.109z");
}

</style>
