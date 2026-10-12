<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="oli_gxb7g"/><path class="g-h7k0thj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:direction-sign-sharp" {...props}></Icon>
<style>
:global(.g-h7k0thj) {
  d: path("M7.5 11.25v-3.5h9M14.25 5.5l2.25 2.25L14.25 10M12 14.25v7");
}

:global(.oli_gxb7g) {
  d: path("M2.75 3.25h18.5v11H2.75z");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
