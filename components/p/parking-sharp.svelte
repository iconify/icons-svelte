<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="okifisbho"/><path class="nhti-ubql"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:parking-sharp" {...props}></Icon>
<style>
:global(.nhti-ubql) {
  d: path("M9.75 16.75v-9.5h3.5a2.75 2.75 0 0 1 0 5.5h-3.5");
}

:global(.okifisbho) {
  d: path("M3.75 3.75h16.5v16.5H3.75z");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
