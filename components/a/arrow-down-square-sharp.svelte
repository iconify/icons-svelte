<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="nciaxcb6w"/><path class="skh6m6vww"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:arrow-down-square-sharp" {...props}></Icon>
<style>
:global(.nciaxcb6w) {
  d: path("M3.25 3.25h17.5v17.5H3.25z");
}

:global(.skh6m6vww) {
  d: path("M12 7.5v8.75m3.75-3.75L12 16.25L8.25 12.5");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
