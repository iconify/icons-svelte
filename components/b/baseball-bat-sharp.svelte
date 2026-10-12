<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="j18zj9mqg"/><circle class="tdcmh-bcw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:baseball-bat-sharp" {...props}></Icon>
<style>
:global(.j18zj9mqg) {
  d: path("m10.39 14.89l8.13-5.87a2.5 2.5 0 0 0-3.54-3.54l-5.87 8.13Zm-.64-.64l-5 5M3.5 18L6 20.5");
}

:global(.tdcmh-bcw) {
  cx: 6.75px;
  cy: 6.75px;
  r: 2.75px;
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
