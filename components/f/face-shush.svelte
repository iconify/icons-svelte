<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><circle class="c6vt1lbds"/><path class="hbw7r9baw"/><path class="yqtpji4ie"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:face-shush" {...props}></Icon>
<style>
:global(.c6vt1lbds) {
  cx: 12px;
  cy: 12px;
  r: 9.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.hbw7r9baw) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8.75 9h.01m6.49 0h.01");
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.yqtpji4ie) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 12.5v5M7.5 16q.75-.5 1.5-.25m7.5.25q-.75-.5-1.5-.25");
}

</style>
