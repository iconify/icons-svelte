<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="d8mt2_n-r"/><circle class="ybj6vw61j"/><path class="e38n76osi"/><path class="ygykp3bfp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:avatar-afro" {...props}></Icon>
<style>
:global(.d8mt2_n-r) {
  cx: 12px;
  cy: 12px;
  r: 6.25px;
}

:global(.e38n76osi) {
  d: path("M9.25 15.25a2.75 2.75 0 0 1 5.5 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ybj6vw61j) {
  cx: 12px;
  cy: 10.5px;
  r: 1.9px;
}

:global(.ygykp3bfp) {
  d: path("M12 2.75a9.25 9.25 0 1 1 0 18.5a9.25 9.25 0 0 1 0-18.5");
}

</style>
