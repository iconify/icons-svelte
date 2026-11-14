<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="d9ltakbhb"/><path class="rq866kbao"/><path class="qz1eedcwb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:bagua-octagon" {...props}></Icon>
<style>
:global(.d9ltakbhb) {
  d: path("M8.5 2.5h7l6 6v7l-6 6h-7l-6-6v-7Z");
}

:global(.qz1eedcwb) {
  d: path("M12 6.5a2.75 2.75 0 0 1 0 5.5a2.75 2.75 0 0 0 0 5.5m0-8.25h.01m-.01 5.5h.01");
}

:global(.rq866kbao) {
  d: path("M6.5 12a5.5 5.5 0 1 0 11 0a5.5 5.5 0 1 0-11 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
