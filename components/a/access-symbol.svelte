<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="aqmj_4big"/><path class="q_jb7mhbr"/><path class="h91sofbbs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:access-symbol" {...props}></Icon>
<style>
:global(.aqmj_4big) {
  width: 18.5px;
  height: 18.5px;
  x: 2.75px;
  y: 2.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 3px;
}

:global(.h91sofbbs) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 9.25v4.25h3.5L17 17h1.25M9.4 11.25a3.75 3.75 0 1 0 5.1 5.25");
}

:global(.q_jb7mhbr) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 6.5h.01");
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
