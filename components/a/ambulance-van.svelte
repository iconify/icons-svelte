<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="ottw80o6z"/><rect class="fzvenabfm"/><path class="d0ca424zn"/><path class="s91v-jwfo"/><path class="j2vmgobzr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:ambulance-van" {...props}></Icon>
<style>
:global(.d0ca424zn) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 11.25h16.5m-14 0L7 8.5h10l.75 2.75m-5.75 2v3.5M10.25 15h3.5");
}

:global(.fzvenabfm) {
  width: 16.5px;
  height: 13px;
  x: 3.75px;
  y: 6px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2.5px;
}

:global(.j2vmgobzr) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 19v2m11-2v2");
}

:global(.ottw80o6z) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.25 3h5.5");
}

:global(.s91v-jwfo) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6.75 15h.01m10.49 0h.01");
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
