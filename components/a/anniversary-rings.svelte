<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="pq9uv809h"/><path class="lszrxibaj"/><path class="dauc5gghs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:anniversary-rings" {...props}></Icon>
<style>
:global(.dauc5gghs) {
  d: path("m12.5 4.25l1.25-1.75h2.5l1.25 1.75l-2.5 3Z");
}

:global(.lszrxibaj) {
  d: path("M9.5 12a5.5 5.5 0 1 0 11 0a5.5 5.5 0 1 0-11 0Z");
}

:global(.pq9uv809h) {
  d: path("M3.5 15a5.5 5.5 0 1 0 11 0a5.5 5.5 0 1 0-11 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
