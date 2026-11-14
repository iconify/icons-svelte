<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="vqljyxdgk"/><path class="j208-7b0m"/><path class="v_xvn4b0c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:file-stack" {...props}></Icon>
<style>
:global(.j208-7b0m) {
  d: path("M6 18V7a2 2 0 0 1 2-2h5.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.v_xvn4b0c) {
  d: path("M3 15V4.5a2 2 0 0 1 2-2h5.5m5 5V10a1.5 1.5 0 0 0 1.5 1.5h2.5");
}

:global(.vqljyxdgk) {
  d: path("M11 7.5h4.5l4 4v8a2 2 0 0 1-2 2H11a2 2 0 0 1-2-2v-10a2 2 0 0 1 2-2Z");
}

</style>
