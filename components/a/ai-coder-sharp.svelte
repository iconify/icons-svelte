<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="dq4m2y2we"/><path class="t0cngecrm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:ai-coder-sharp" {...props}></Icon>
<style>
:global(.dq4m2y2we) {
  d: path("M4.25 4.25h15.5v11H4.25zm-1.5 15h18.5");
}

:global(.t0cngecrm) {
  d: path("m9.75 7.75l-2 2l2 2m4.5-4l2 2l-2 2");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
