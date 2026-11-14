<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="mlibkbluq"/><path class="l56b1ab2g"/><path class="yo-mktbdh"/><path class="ycdl3bbay"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:chart-arc-diagram" {...props}></Icon>
<style>
:global(.l56b1ab2g) {
  d: path("M9 19a5.75 13 0 0 1 11.5 0");
}

:global(.mlibkbluq) {
  d: path("M2.5 19h19m-18 0a5.5 9 0 0 1 11 0");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ycdl3bbay) {
  fill: currentColor;
  d: path("M2 19a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm5.5 0a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm5.5 0a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm6 0a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Z");
}

:global(.yo-mktbdh) {
  d: path("M14.5 19a3 5 0 0 1 6 0");
}

</style>
