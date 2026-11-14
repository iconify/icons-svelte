<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="q4yctbgpi"/><path class="elrn8_h6c"/><path class="ml6m0obaj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:bucket-replication" {...props}></Icon>
<style>
:global(.elrn8_h6c) {
  d: path("m2.5 5l2 14.5q3.49 1.074 6.981.995m7.127-9.029L19.5 5M17 17h4.75v4.75H17Z");
}

:global(.ml6m0obaj) {
  d: path("M14.25 19.75v-4.5a1 1 0 0 1 1-1h4.5");
}

:global(.q4yctbgpi) {
  d: path("M2.5 5a8.5 2 0 1 0 17 0a8.5 2 0 1 0-17 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
