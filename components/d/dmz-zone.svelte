<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="bwxp2jbki"/><rect class="bpqciuchf"/><path class="pp7fsrb1k"/><rect class="fnuhxvbeh"/><path class="j7ybonb5d"/><path class="jt9wyzbdh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:dmz-zone" {...props}></Icon>
<style>
:global(.bpqciuchf) {
  width: 3.75px;
  height: 18.5px;
  x: 17.5px;
  y: 2.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 1.25px;
}

:global(.bwxp2jbki) {
  width: 3.75px;
  height: 18.5px;
  x: 2.75px;
  y: 2.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 1.25px;
}

:global(.fnuhxvbeh) {
  width: 6px;
  height: 12px;
  x: 9px;
  y: 6px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 1.75px;
}

:global(.j7ybonb5d) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11 9.5h2m-2 3h2");
}

:global(.jt9wyzbdh) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 15.25h.01");
}

:global(.pp7fsrb1k) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 8.75H6.5m-3.75 6.5H6.5m11-6.5h3.75m-3.75 6.5h3.75");
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
