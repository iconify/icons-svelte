<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="te9g9hvsl"/><path class="tvy1nw5_u"/><path class="bmzpudbhs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:coins-crypto" {...props}></Icon>
<style>
:global(.bmzpudbhs) {
  d: path("M3 15.5V19a6.5 2.5 0 0 0 13 0v-3.5m-1.25-10a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0Z");
}

:global(.te9g9hvsl) {
  d: path("M3 12a6.5 2.5 0 1 0 13 0a6.5 2.5 0 1 0-13 0Z");
}

:global(.tvy1nw5_u) {
  d: path("M3 12v3.5a6.5 2.5 0 0 0 13 0V12");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
