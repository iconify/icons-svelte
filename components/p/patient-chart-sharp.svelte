<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="ekl-hdcsc"/><path class="zzm-nmnsa"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:patient-chart-sharp" {...props}></Icon>
<style>
:global(.ekl-hdcsc) {
  d: path("M4.75 5.5h14.5v15.75H4.75zM9 5.5V2.75h6V5.5Z");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.zzm-nmnsa) {
  d: path("M8 9.5h8m-8 3h5m-5.25 4h2L11 14l1.5 4l1.25-2.5h2.5");
}

</style>
