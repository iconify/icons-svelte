<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="he2n2pkfg"/><path class="nr2kwkbiv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:payroll-journal" {...props}></Icon>
<style>
:global(.he2n2pkfg) {
  d: path("M21 12.567V3.5q-6-.75-9 1.5q-3-2.25-9-1.5V16q5.348-.669 8.313 1.046M12 5v10.1M5.75 8.5h3.5m5.5 0h3.5M14 18a3 3 0 1 0 6 0a3 3 0 1 0-6 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.nr2kwkbiv) {
  d: path("M17 15h2a3 3 0 0 1 0 6h-2");
}

</style>
