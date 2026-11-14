<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="flz-kvcjc"/><path class="u2mt7yxfa"/><path class="is8nqnbzt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:payroll-reconciliation" {...props}></Icon>
<style>
:global(.flz-kvcjc) {
  d: path("M12.6 17H2.5V4.5h19v10.8");
}

:global(.is8nqnbzt) {
  d: path("M16.75 14.5L18 15.75L16.75 17");
}

:global(.u2mt7yxfa) {
  d: path("M9.25 10.75a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0Zm11.5 7.75A2.75 2.75 0 1 1 18 15.75");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
