<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ujgeyzb3n"/><path class="ackg-fb3x"/><path class="ir_1-rbys"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:cling-wrap-box" {...props}></Icon>
<style>
:global(.ackg-fb3x) {
  d: path("M9.5 12L16 9l5 1.5V17");
}

:global(.ir_1-rbys) {
  d: path("M6.5 15a3 3 0 1 0 6 0a3 3 0 1 0-6 0Zm3 0h.01");
}

:global(.ujgeyzb3n) {
  d: path("M3 9h13v12H3V9l1.5-6.25");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
