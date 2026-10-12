<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="uskr93buo"/><path class="n_7qvw31r"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:front-defrost-sharp" {...props}></Icon>
<style>
:global(.n_7qvw31r) {
  d: path("M8.5 15.5c-1-1.25 1-2.5 0-3.75s1-2.5 0-3.75m3.5 7.5c-1-1.25 1-2.5 0-3.75s1-2.5 0-3.75m3.5 7.5c-1-1.25 1-2.5 0-3.75s1-2.5 0-3.75");
}

:global(.uskr93buo) {
  d: path("M3.25 8.5c2.5-2 5.5-3 8.75-3s6.25 1 8.75 3l-2 10.25c-2-.75-4.25-1.25-6.75-1.25s-4.75.5-6.75 1.25Z");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
