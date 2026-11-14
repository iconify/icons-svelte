<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="e806y8boy"/><path class="x99fvy-7v"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:condition-monitoring" {...props}></Icon>
<style>
:global(.e806y8boy) {
  d: path("M3 4.5h14v13H3Zm2.5 13l-1 3h11l-1-3M17 11h4.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.x99fvy-7v) {
  d: path("M5.5 11h2L9 8l2 6l1.5-3h2");
}

</style>
