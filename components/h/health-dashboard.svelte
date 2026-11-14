<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="m6kvr71pk"/><path class="n2wiosvse"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:health-dashboard" {...props}></Icon>
<style>
:global(.m6kvr71pk) {
  d: path("M2.5 3h19v13.5h-19ZM12 16.5V20m-4 .5h8");
}

:global(.n2wiosvse) {
  d: path("M5.5 6h6v7.5h-6Zm2 5.5v-2m2 2V8m4 1.75a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
