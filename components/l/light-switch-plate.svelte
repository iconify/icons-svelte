<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="f18_f1p2j"/><path class="mx1-zgbkf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:light-switch-plate" {...props}></Icon>
<style>
:global(.f18_f1p2j) {
  d: path("M5.5 2.5h13v19h-13Z");
}

:global(.mx1-zgbkf) {
  d: path("M9 8h6v8H9Zm0 4h6m-3-6.75h.01M12 18.75h.01");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
