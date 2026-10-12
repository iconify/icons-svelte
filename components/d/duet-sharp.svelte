<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="adjr2do3c"/><circle class="v4wf3czoy"/><path class="k96j4-b7r"/><circle class="phidi_btw"/><path class="b3_k96hhs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:duet-sharp" {...props}></Icon>
<style>
:global(.adjr2do3c) {
  d: path("M2.75 3.75h18.5v16.5H2.75zm9.25 0v16.5");
}

:global(.b3_k96hhs) {
  d: path("M14.1 16a2.5 2.5 0 0 1 5 0");
}

:global(.k96j4-b7r) {
  d: path("M4.9 16a2.5 2.5 0 0 1 5 0");
}

:global(.phidi_btw) {
  cx: 16.6px;
  cy: 10px;
  r: 1.75px;
}

:global(.v4wf3czoy) {
  cx: 7.4px;
  cy: 10px;
  r: 1.75px;
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
