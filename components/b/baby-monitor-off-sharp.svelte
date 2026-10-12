<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="vx64dqb8q"/><path class="u1nac14xb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:baby-monitor-off-sharp" {...props}></Icon>
<style>
:global(.u1nac14xb) {
  d: path("M8.75 9.75h6.5v5h-6.5zM10 18h4");
}

:global(.vx64dqb8q) {
  d: path("M15 7.25v-4.5m-8.75 4.5h11.5v14H6.25z");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
