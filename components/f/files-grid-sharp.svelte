<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="o6jb8yb7y"/><path class="d9rsgr4ju"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:files-grid-sharp" {...props}></Icon>
<style>
:global(.d9rsgr4ju) {
  d: path("M8.25 2.75h7.5l4.5 4.5v10.5");
}

:global(.o6jb8yb7y) {
  d: path("M12.25 5.75h-8.5v15.5h12.5V9.75Z");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
