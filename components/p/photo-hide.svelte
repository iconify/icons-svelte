<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="bdbbekzrx"/><path class="as5-kdbtt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:photo-hide" {...props}></Icon>
<style>
:global(.as5-kdbtt) {
  d: path("m2.5 16.5l6-6L13 15m-.5-6a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm2 9q3.5-3.5 7 0q-3.5 3.5-7 0Zm.75 3l5.5-6");
}

:global(.bdbbekzrx) {
  d: path("M11.6 19H2.5V4h18v7.2");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
