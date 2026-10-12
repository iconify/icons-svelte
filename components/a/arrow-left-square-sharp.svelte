<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="nciaxcb6w"/><path class="rpiz0hb3i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:arrow-left-square-sharp" {...props}></Icon>
<style>
:global(.nciaxcb6w) {
  d: path("M3.25 3.25h17.5v17.5H3.25z");
}

:global(.rpiz0hb3i) {
  d: path("M16.5 12H7.75m3.75 3.75L7.75 12l3.75-3.75");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
