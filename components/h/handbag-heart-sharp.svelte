<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="sy5ae1b2m"/><path class="wbvnnxx9u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:handbag-heart-sharp" {...props}></Icon>
<style>
:global(.sy5ae1b2m) {
  d: path("M6.75 9.25h12l.32 1.47l1.86 8.56l.32 1.47H2.75l.32-1.47l1.86-8.56l.32-1.47zm1.25 0V7.5a4 4 0 0 1 8 0v1.75");
}

:global(.wbvnnxx9u) {
  d: path("M10 12h4v3h-4z");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
