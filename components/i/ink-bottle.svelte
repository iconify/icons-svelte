<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="h401gyb5z"/><path class="bpn1dvbrh"/><rect class="f_eh8fbwn"/><path class="p56x52bao"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:ink-bottle" {...props}></Icon>
<style>
:global(.bpn1dvbrh) {
  d: path("M9.75 7.25v3m4.5-3v3");
}

:global(.f_eh8fbwn) {
  width: 16.5px;
  height: 11px;
  x: 3.75px;
  y: 10.25px;
  rx: 3px;
}

:global(.h401gyb5z) {
  width: 7.5px;
  height: 4.5px;
  x: 8.25px;
  y: 2.75px;
  rx: 1.5px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.p56x52bao) {
  d: path("M6.75 14.75h10.5v2.5a1.5 1.5 0 0 1-1.5 1.5h-7.5a1.5 1.5 0 0 1-1.5-1.5Z");
}

</style>
