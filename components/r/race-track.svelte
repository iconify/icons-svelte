<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="z3z9c3b0s"/><path class="usuxgabme"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:race-track" {...props}></Icon>
<style>
:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.usuxgabme) {
  d: path("M7 15a5 1.75 0 1 0 10 0a5 1.75 0 1 0-10 0Z");
}

:global(.z3z9c3b0s) {
  d: path("M2.5 15a9.5 5.5 0 1 0 19 0a9.5 5.5 0 1 0-19 0ZM12 9.5v-7m0 0h5.5v4H12Z");
}

</style>
