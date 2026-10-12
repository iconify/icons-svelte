<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><circle class="c6vt1lbds"/><path class="hbw7r9baw"/><path class="uepfe-01w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:face-shush-sharp" {...props}></Icon>
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

:global(.uepfe-01w) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 12.5v5M7.5 16l.75-.5l.75.25m7.5.25l-.75-.5l-.75.25");
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
