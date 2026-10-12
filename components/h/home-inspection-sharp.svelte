<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="mzu4kqeuf"/><circle class="ygphxfbhc"/><path class="pmw3q5b0z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:home-inspection-sharp" {...props}></Icon>
<style>
:global(.mzu4kqeuf) {
  d: path("M2.75 18.75V8.55l.78-.62l5.69-4.55l.78-.63l.78.63l5.69 4.55l.78.62v1.7a7 7 0 0 0-7 7v2.5h-7.5z");
}

:global(.pmw3q5b0z) {
  d: path("m15.5 17.25l1.25 1.25L19 16");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ygphxfbhc) {
  cx: 17.25px;
  cy: 17.25px;
  r: 4px;
}

</style>
