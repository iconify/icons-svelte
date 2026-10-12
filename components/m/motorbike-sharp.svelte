<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="wpd6f3bzf"/><circle class="ekz86bcsq"/><path class="ridn67wav"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:motorbike-sharp" {...props}></Icon>
<style>
:global(.ekz86bcsq) {
  cx: 18.25px;
  cy: 18px;
  r: 3px;
}

:global(.ridn67wav) {
  d: path("M4 10h4.75l.5-.87v-.01l.5-.87H13l.38.92l.99 2.41l.38.92H3V10zm10.25-4H16l1.7 9.05");
}

:global(.wpd6f3bzf) {
  cx: 5.75px;
  cy: 18px;
  r: 3px;
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
