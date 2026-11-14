<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="q0f-lgkcm"/><path class="tyx27jhsf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:eye-chart" {...props}></Icon>
<style>
:global(.q0f-lgkcm) {
  d: path("M5 2.5h14v19H5Z");
}

:global(.tyx27jhsf) {
  d: path("M14.5 5.5h-5V11h5m-5-2.75h4m-5 6.25h7M10 18h4");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
