<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="hmha9xhbi"/><path class="v8pwi-q0s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:power-window-sharp" {...props}></Icon>
<style>
:global(.hmha9xhbi) {
  d: path("m4.08 9.51l3.34-3.77l1.33-1.49h5.5v16H2.75V11z");
}

:global(.v8pwi-q0s) {
  d: path("m6.25 11l3.5-3.75h1.75V11Zm13-6.25v14.5m-2-12.5l2-2l2 2m-4 10.5l2 2l2-2");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
