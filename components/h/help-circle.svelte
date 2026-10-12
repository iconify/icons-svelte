<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><circle class="c6vt1lbds"/><path class="xrk2mwrrz"/><path class="b0008obhs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:help-circle" {...props}></Icon>
<style>
:global(.b0008obhs) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 16.75h.01");
}

:global(.c6vt1lbds) {
  cx: 12px;
  cy: 12px;
  r: 9.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.xrk2mwrrz) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.6 9.4a2.5 2.5 0 1 1 3.4 2.35c-.6.25-1 .8-1 1.45v.55");
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
