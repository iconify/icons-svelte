<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="bh4biibbp"/><path class="try0szbvy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:menu-card-search-sharp" {...props}></Icon>
<style>
:global(.bh4biibbp) {
  d: path("M4.75 2.75h14.5v18.5H4.75z");
}

:global(.try0szbvy) {
  d: path("M8.5 10.75a3.5 3.5 0 0 1 7 0m-7.75 0h8.5m-8 4h7.5m-6.25 3h5");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
