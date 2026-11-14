<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ua6p6bb_g"/><path class="d6pp-1ias"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:commercial-property" {...props}></Icon>
<style>
:global(.d6pp-1ias) {
  d: path("M8.5 12.5h7v8h-7Z");
}

:global(.ua6p6bb_g) {
  d: path("M4 8h16v12.5H4ZM3 8l2-4h14l2 4");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
