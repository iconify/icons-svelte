<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="doki3kq2c"/><circle class="w6ucblb_v"/><path class="e_mqbzbed"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:eye-anatomy-sharp" {...props}></Icon>
<style>
:global(.doki3kq2c) {
  d: path("M6.44 8.5a7 7 0 1 1 0 7c-2.19-1-2.19-6 0-7Z");
}

:global(.e_mqbzbed) {
  d: path("M19.5 12h1.75");
}

:global(.w6ucblb_v) {
  cx: 9.5px;
  cy: 12px;
  r: 1.5px;
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
