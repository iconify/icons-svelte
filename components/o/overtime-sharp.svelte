<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="dldnhmbjp"/><path class="kt8ta-bfj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:overtime-sharp" {...props}></Icon>
<style>
:global(.dldnhmbjp) {
  d: path("M12 21.25A9.25 9.25 0 1 1 21.25 12");
}

:global(.kt8ta-bfj) {
  d: path("M12 7.25V12l-3 2m9 .5v6m-3-3h6");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
