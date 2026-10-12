<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="fgkpf5b9v"/><circle class="sf-oocn4o"/><path class="bbpfwnbwk"/><path class="saibhebxm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:disco-ball" {...props}></Icon>
<style>
:global(.bbpfwnbwk) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 9.5h.01M8.5 13h.01m6.99 0h.01M12 16.5h.01");
}

:global(.fgkpf5b9v) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.75v2");
}

:global(.saibhebxm) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M19.5 2.75q.21 1.54 1.75 1.75q-1.54.21-1.75 1.75q-.21-1.54-1.75-1.75q1.54-.21 1.75-1.75");
}

:global(.sf-oocn4o) {
  cx: 12px;
  cy: 13px;
  r: 8.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
