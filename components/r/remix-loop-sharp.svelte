<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="vr4wc0bze"/><circle class="o5wl3acgc"/><path class="zk-s8gb5o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:remix-loop-sharp" {...props}></Icon>
<style>
:global(.o5wl3acgc) {
  cx: 10.25px;
  cy: 14.25px;
  r: 1.75px;
}

:global(.vr4wc0bze) {
  d: path("M20.25 12a8.25 8.25 0 0 1-14.6 5.25M3.75 12a8.25 8.25 0 0 1 14.6-5.25m.15-3.25v3.25h-3.25M5.5 20.5v-3.25h3.25");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.zk-s8gb5o) {
  d: path("M12 14.25V8.5l2.75 1");
}

</style>
