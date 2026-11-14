<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="casj1hb2c"/><path class="qxk0kebul"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:appointment-reminder" {...props}></Icon>
<style>
:global(.casj1hb2c) {
  d: path("M11.4 20.5H3.5V5h17v7.1M8 3v4m8-4v4M3.5 10h17m-13 3.5h.01m3.74 0h.01M7.5 17.25h.01");
}

:global(.qxk0kebul) {
  d: path("M15.25 20v-2.75c0-1.65 1.25-3 2.75-3s2.75 1.35 2.75 3V20Zm-1 0h7.5m-4.5 1.75h1.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
