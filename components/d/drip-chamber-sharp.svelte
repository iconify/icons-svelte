<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="lgaeyobtl"/><path class="oah4cxijy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:drip-chamber-sharp" {...props}></Icon>
<style>
:global(.lgaeyobtl) {
  d: path("M12 2.75v3m0 11.5v4M7.75 5.75h8.5v11.5h-8.5z");
}

:global(.oah4cxijy) {
  d: path("m12 7.75l1.5 2v.7a1.5 1.5 0 0 1-3 0v-.7zM7.75 14.5h8.5");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
