<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="vo0ftlb9f"/><circle class="wwna4hbmj"/><path class="cgg5lxbum"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:daycare-sharp" {...props}></Icon>
<style>
:global(.cgg5lxbum) {
  d: path("M9 18.75V17.5a3 3 0 0 1 3-3a3 3 0 0 1 3 3v1.25Z");
}

:global(.vo0ftlb9f) {
  d: path("M3.75 10.6v-.921l.7-.599l6.25-5.4L12 2.568l1.3 1.112l6.25 5.4l.7.599V21.25H3.75v-2Z");
}

:global(.wwna4hbmj) {
  cx: 12px;
  cy: 10.25px;
  r: 2px;
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
