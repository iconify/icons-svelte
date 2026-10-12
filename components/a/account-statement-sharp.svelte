<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="mqkg9kykg"/><path class="tgulksb_j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:account-statement-sharp" {...props}></Icon>
<style>
:global(.mqkg9kykg) {
  d: path("M4.25 2.75h15.5v18.5H4.25z");
}

:global(.tgulksb_j) {
  d: path("m8 8.25l4-2.5l4 2.5Zm-.25 3.25h8.5m-8.5 3h8.5m-8.5 3h5");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
