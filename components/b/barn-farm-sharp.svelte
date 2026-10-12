<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="dti-we-6p"/><path class="fc9-vfzxi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:barn-farm-sharp" {...props}></Icon>
<style>
:global(.dti-we-6p) {
  d: path("M2.75 20.45v-10.2l.58-.55l4.59-4.4l.58-.55l.58.55l4.59 4.4l.58.55v11H2.75z");
}

:global(.fc9-vfzxi) {
  d: path("M6 21.25v-5h5v5m-5-5l5 5m0-5l-5 5m1.5-10.5h2m7.75 10.5V6.75h4v14.5Z");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
