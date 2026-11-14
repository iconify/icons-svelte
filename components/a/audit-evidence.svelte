<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="tfss18bua"/><path class="uz9f1pbvt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:audit-evidence" {...props}></Icon>
<style>
:global(.tfss18bua) {
  d: path("M3 20.5V7a1.5 1.5 0 0 1 1.5-1.5H7L8.5 7m0 6V3h8v10m0-8h3v8");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.uz9f1pbvt) {
  d: path("M3 20.5L5.5 13h16L19 20.5Zm7.5-13L12 9l2.75-2.75");
}

</style>
