<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="i1nywkjmg"/><path class="yvsd53hxb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:due-date-sharp" {...props}></Icon>
<style>
:global(.i1nywkjmg) {
  d: path("M3.75 4.75h16.5v16.5H3.75zm0 5.25h16.5M8 2.75v4m8-4v4");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.yvsd53hxb) {
  d: path("M9 18.25V13h6l-1.5 1.75L15 16.5H9");
}

</style>
