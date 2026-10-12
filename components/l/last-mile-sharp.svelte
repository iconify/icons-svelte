<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="o6h79r7ib"/><path class="n9zurybxd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:last-mile-sharp" {...props}></Icon>
<style>
:global(.n9zurybxd) {
  d: path("M8.75 13.25h6.5V19h-6.5zm3.25 0v2");
}

:global(.o6h79r7ib) {
  d: path("M3.75 10.4v-.461l.35-.299l7.25-6.2l.65-.556l.65.556l7.25 6.2l.35.299V21.25H3.75v-1.5Z");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
