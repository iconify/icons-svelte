<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="q0f-lgkcm"/><path class="e0beztq-y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:capacity-utilization" {...props}></Icon>
<style>
:global(.e0beztq-y) {
  d: path("M5 7.25q3.5-1.75 7 0t7 0M5 12h2.5M5 16h2.5");
}

:global(.q0f-lgkcm) {
  d: path("M5 2.5h14v19H5Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
