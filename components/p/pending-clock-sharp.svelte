<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="rjc1od8nf"/><path class="f3dn4mblz"/><path class="be9ax0akk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:pending-clock-sharp" {...props}></Icon>
<style>
:global(.be9ax0akk) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M14.25 18h.01m3.24 0h.01m3.24 0h.01");
}

:global(.f3dn4mblz) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 7.25V12l-3 2");
}

:global(.rjc1od8nf) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 21.25A9.25 9.25 0 1 1 21.25 12");
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
