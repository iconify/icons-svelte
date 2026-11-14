<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="u_f-ygbmh"/><path class="vgtwf4b4i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:parking-bay-family" {...props}></Icon>
<style>
:global(.u_f-ygbmh) {
  d: path("M2 21.5v-19h20v19");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.vgtwf4b4i) {
  d: path("M6 7.75a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0ZM5 21.5v-4a3.5 3.5 0 0 1 7 0v4m3.25-9a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0Zm-.5 9v-2.25a2.25 2.25 0 0 1 4.5 0v2.25");
}

</style>
