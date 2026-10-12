<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="k7h082b9n"/><path class="hynzddbgn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:corner-down-right-sharp" {...props}></Icon>
<style>
:global(.hynzddbgn) {
  d: path("m15.5 11l3.75 3.75l-3.75 3.75");
}

:global(.k7h082b9n) {
  d: path("M4.25 4.25v10.5h15");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
