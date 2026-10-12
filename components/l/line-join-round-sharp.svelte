<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="m3ce0y_pa"/><path class="qr9-o6rkg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:line-join-round-sharp" {...props}></Icon>
<style>
:global(.m3ce0y_pa) {
  d: path("M2.75 5.25h13v16m-13-7.5h4.5v7.5");
}

:global(.qr9-o6rkg) {
  d: path("M2.75 9.5h8.75v11.75");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
