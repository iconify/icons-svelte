<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="orgv_og6z"/><path class="iozc9zhuw"/><path class="k49j5ob_j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:autofill" {...props}></Icon>
<style>
:global(.iozc9zhuw) {
  fill: currentColor;
  d: path("M11.75 17.25h2.5v2.5h-2.5Z");
}

:global(.k49j5ob_j) {
  d: path("M18.5 4v16.5M16 18l2.5 2.5L21 18");
}

:global(.orgv_og6z) {
  d: path("M3 2.5h10v16H3Zm0 5.25h10m-10 5.5h10");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
