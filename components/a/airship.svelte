<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="xrhbezbul"/><path class="agsrerbqn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:airship" {...props}></Icon>
<style>
:global(.agsrerbqn) {
  d: path("M10 13.5h5V17h-5ZM4.5 7l-2-2.5m2 8.5l-2 2.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.xrhbezbul) {
  d: path("M3.5 10a8.5 4.5 0 1 0 17 0a8.5 4.5 0 1 0-17 0Z");
}

</style>
