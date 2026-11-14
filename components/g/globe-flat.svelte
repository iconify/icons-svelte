<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="hn7tnnbwb"/><path class="cuxpb1b0o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:globe-flat" {...props}></Icon>
<style>
:global(.cuxpb1b0o) {
  d: path("M7.5 12a4.5 7 0 1 0 9 0a4.5 7 0 1 0-9 0Zm-5 0h19");
}

:global(.hn7tnnbwb) {
  d: path("M2.5 5h19v14h-19Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
