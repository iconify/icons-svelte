<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="qgdakr69k"/><path class="zwk-9lbqf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:ab-test-model" {...props}></Icon>
<style>
:global(.qgdakr69k) {
  fill: currentColor;
  d: path("M2.5 5.5H9v13H2.5Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.zwk-9lbqf) {
  d: path("M15 5.5h6.5v13H15Zm-3 0v2m0 3.5v2m0 3.5v2");
}

</style>
