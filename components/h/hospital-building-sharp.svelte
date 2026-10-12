<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="umzr--bdp"/><path class="k4nt94wnr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:hospital-building-sharp" {...props}></Icon>
<style>
:global(.k4nt94wnr) {
  d: path("M10 21.25v-4h4v4");
}

:global(.umzr--bdp) {
  d: path("M2.75 9h18.5v12.25H2.75zM12 2.75v4.5M9.75 5h4.5m-8 7.5v2m0 2.5v2m11.5-6.5v2m0 2.5v2M12 12.5V14");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
