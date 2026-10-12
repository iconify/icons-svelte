<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="tn8wl4wgg"/><path class="d6qn0tbqp"/><path class="n3q3-os0w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:octahedron-sharp" {...props}></Icon>
<style>
:global(.d6qn0tbqp) {
  d: path("m12 4l-.5 9l.5 7");
}

:global(.n3q3-os0w) {
  d: path("m6.25 12.05l5.25.95l6.5-1.15");
}

:global(.tn8wl4wgg) {
  d: path("m12.87 3.4l7.01 7.2l.87.9l-.82.94l-7.11 8.12l-.82.94l-.82-.94l-7.11-8.12l-.82-.94l.87-.9l7.01-7.2l.87-.9z");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
