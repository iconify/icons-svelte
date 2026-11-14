<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="lp4kqsb9r"/><path class="h6qpxusje"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:copy-settings" {...props}></Icon>
<style>
:global(.h6qpxusje) {
  d: path("M7.5 7V4.5a2 2 0 0 1 2-2H19a2 2 0 0 1 2 2V15a2 2 0 0 1-2 2h-2.5M6 11.5h7.5M6 17h7.5M7 11.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm3 5.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Z");
}

:global(.lp4kqsb9r) {
  d: path("M3 7h13.5v14.5H3Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
