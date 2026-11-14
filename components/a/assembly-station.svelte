<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="nngwmgbxf"/><path class="x-utcfczg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:assembly-station" {...props}></Icon>
<style>
:global(.nngwmgbxf) {
  d: path("M3.75 15h13.5v3H3.75Zm5.5-4.5h8V15h-8Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.x-utcfczg) {
  d: path("M10.75 5.5h9.5V21h-6v-3m-1-15.5v8m-2.5-8h5");
}

</style>
