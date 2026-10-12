<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="d8mt2_n-r"/><circle class="ybj6vw61j"/><path class="e38n76osi"/><path class="y3j0g38tz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:avatar-visor-sharp" {...props}></Icon>
<style>
:global(.d8mt2_n-r) {
  cx: 12px;
  cy: 12px;
  r: 6.25px;
}

:global(.e38n76osi) {
  d: path("M9.25 15.25a2.75 2.75 0 0 1 5.5 0");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.y3j0g38tz) {
  d: path("M12 2.75a9.25 9.25 0 1 1 0 18.5a9.25 9.25 0 0 1 0-18.5Z");
}

:global(.ybj6vw61j) {
  cx: 12px;
  cy: 10.5px;
  r: 1.9px;
}

</style>
