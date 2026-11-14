<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="sptvl1v9d"/><path class="pa8r7vbdn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:factory-check" {...props}></Icon>
<style>
:global(.pa8r7vbdn) {
  d: path("M6 13h3.5v6H6Zm8.75 5l2 2L21 15.75");
}

:global(.sptvl1v9d) {
  d: path("M11.8 19H2.5V9l6-4.5V9l6-4.5V9l6-4.5v7.8");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
