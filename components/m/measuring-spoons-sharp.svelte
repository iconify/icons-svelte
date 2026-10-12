<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="e11cb2_va"/><path class="lnde3sgwb"/><path class="df77rtb-r"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:measuring-spoons-sharp" {...props}></Icon>
<style>
:global(.df77rtb-r) {
  d: path("M16.75 20.75a3.5 2.5 90 1 1 0-7a3.5 2.5 90 1 1 0 7Zm.05-7l.4-5.5");
}

:global(.e11cb2_va) {
  cx: 17.25px;
  cy: 5.75px;
  r: 2.5px;
}

:global(.lnde3sgwb) {
  d: path("M4 18.75a4.25 3-45 1 1 6-6a4.25 3-45 1 1-6 6Zm6-6l5.45-5.25");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
