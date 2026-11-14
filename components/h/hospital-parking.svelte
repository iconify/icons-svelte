<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="obhedbbfr"/><path class="p0ttb6bye"/><path class="n0q0gac6b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:hospital-parking" {...props}></Icon>
<style>
:global(.n0q0gac6b) {
  fill: currentColor;
  d: path("M16.5 14.25h3v2.25h2.25v3H19.5v2.25h-3V19.5h-2.25v-3h2.25Z");
}

:global(.obhedbbfr) {
  d: path("M11.4 15H3V2.5h13v8.9M9.5 15v6.5");
}

:global(.p0ttb6bye) {
  d: path("M7.25 12V5.5H10c1.4 0 2.5 1.1 2.5 2.5s-1.1 2.5-2.5 2.5H7.25");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
