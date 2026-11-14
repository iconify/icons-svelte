<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="mex4oubwi"/><path class="ye9jnqbpm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:pin-furniture" {...props}></Icon>
<style>
:global(.mex4oubwi) {
  d: path("M4.5 11V7A2.5 2.5 0 0 1 7 4.5h10A2.5 2.5 0 0 1 19.5 7v4");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ye9jnqbpm) {
  d: path("M2.5 13a2 2 0 0 1 4 0v2h11v-2a2 2 0 0 1 4 0v5.5h-19ZM5 18.5v2m14-2v2");
}

</style>
