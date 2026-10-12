<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="hmz588b6d"/><path class="n_7qvw31r"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:rear-defrost-sharp" {...props}></Icon>
<style>
:global(.hmz588b6d) {
  d: path("M2.75 5.25h18.5v13.5H2.75z");
}

:global(.n_7qvw31r) {
  d: path("M8.5 15.5c-1-1.25 1-2.5 0-3.75s1-2.5 0-3.75m3.5 7.5c-1-1.25 1-2.5 0-3.75s1-2.5 0-3.75m3.5 7.5c-1-1.25 1-2.5 0-3.75s1-2.5 0-3.75");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
