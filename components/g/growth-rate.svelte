<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="vp4mrabmz"/><path class="vefwv_bky"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:growth-rate" {...props}></Icon>
<style>
:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.vefwv_bky) {
  d: path("M13.25 4.25L17 4l.75 3.75m-3 13.5l6.5-6.5m-5.75.75h.01m4.99 5h.01");
}

:global(.vp4mrabmz) {
  d: path("M2.5 14.5c4 0 7 0 9-2.5L17 4");
}

</style>
