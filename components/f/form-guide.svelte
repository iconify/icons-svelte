<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="pz3s46b5u"/><path class="tbvu42bzd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:form-guide" {...props}></Icon>
<style>
:global(.pz3s46b5u) {
  d: path("M2.5 6a2 2 0 0 1 2-2h14l3 3v11a2 2 0 0 1-2 2h-15a2 2 0 0 1-2-2Z");
}

:global(.tbvu42bzd) {
  d: path("M18.5 4v3h3M4.75 10L6 15l1.25-3.5L8.5 15l1.25-5m2 0v5h2.5m2-5v5h.5a2.5 2.5 0 0 0 0-5Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
