<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="gbxhd3bye"/><path class="v6ixyccmb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:centrifugal-pump" {...props}></Icon>
<style>
:global(.gbxhd3bye) {
  d: path("M5 13.5a6 6 0 1 0 12 0a6 6 0 1 0-12 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.v6ixyccmb) {
  d: path("M13.5 8V3h4v8M4 21.5h14m-9-8a2 2 0 1 0 4 0a2 2 0 1 0-4 0Z");
}

</style>
