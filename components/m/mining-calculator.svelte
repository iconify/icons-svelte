<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="mvtlwwbli"/><path class="osp-dcbla"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:mining-calculator" {...props}></Icon>
<style>
:global(.mvtlwwbli) {
  d: path("M10.6 21.5H3.5v-19h14v9.2");
}

:global(.osp-dcbla) {
  d: path("M6.5 5.5h8V9h-8Zm1 7.5h.01M12 13h.01M7.5 17.5h.01m6.99 4l5-5m-3.25-2.25q3.75 1.75 5.5 5.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
