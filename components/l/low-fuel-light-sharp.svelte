<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="bu9o55b5e"/><path class="megl4yadw"/><path class="kf6swqmmh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:low-fuel-light-sharp" {...props}></Icon>
<style>
:global(.bu9o55b5e) {
  d: path("M3 2.75h10.5v18.5H3z");
}

:global(.kf6swqmmh) {
  d: path("M6 15.25h4.5v3H6zM13.5 8h3.75v10.25h3V7.5L18 5.25");
}

:global(.megl4yadw) {
  d: path("M6 5.75h4.5v12.5H6Z");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
