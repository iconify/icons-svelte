<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="q1_kx380q"/><path class="pqns4qbqd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:reply" {...props}></Icon>
<style>
:global(.pqns4qbqd) {
  d: path("m9.5 6l-5 5l5 5");
}

:global(.q1_kx380q) {
  d: path("M4.5 11H14a5.5 5.5 0 0 1 5.5 5.5V19");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
