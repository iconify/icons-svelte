<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="dbgvcxwad"/><path class="v1tklhylv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:no-guns-sharp" {...props}></Icon>
<style>
:global(.dbgvcxwad) {
  cx: 12px;
  cy: 12px;
  r: 9.25px;
}

:global(.v1tklhylv) {
  d: path("M6.5 9h10v2.75h-6L9.75 16H7.5l.5-4.25H6.5Zm4.25 2.75v1.5h1.5M5.5 5.5l13 13");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
