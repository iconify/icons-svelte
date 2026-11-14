<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rp7lr2bkz"/><path class="f9s30ubuo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:medical-coding" {...props}></Icon>
<style>
:global(.f9s30ubuo) {
  d: path("M6 7.25a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0M12.25 11l-1 5.5m4-6l-1 5.5M10 12.75h6.25M9.5 15h6.25");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.rp7lr2bkz) {
  d: path("M5.625 3h4.288a2.63 2.63 0 0 1 1.856.769l7.375 7.375a2.625 2.625 0 0 1 0 3.712l-4.288 4.288a2.625 2.625 0 0 1-3.712 0l-7.375-7.375A2.63 2.63 0 0 1 3 9.913V5.625A2.625 2.625 0 0 1 5.625 3");
}

</style>
