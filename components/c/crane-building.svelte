<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qed6m1bau"/><rect class="i3a8og2pw"/><path class="bjel46bwo"/><rect class="rdkisebvg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:crane-building" {...props}></Icon>
<style>
:global(.bjel46bwo) {
  d: path("M13.25 18.25h1.5m2.25 0h1.5m-1-12.75v4");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.i3a8og2pw) {
  width: 11px;
  height: 5.75px;
  x: 10.25px;
  y: 15.5px;
  rx: 1px;
}

:global(.qed6m1bau) {
  d: path("M5.5 21.25V2.75M2.75 5.5h18.5M3.5 21.25h4");
}

:global(.rdkisebvg) {
  width: 4px;
  height: 3px;
  x: 15.5px;
  y: 9.5px;
  rx: 0.5px;
}

</style>
