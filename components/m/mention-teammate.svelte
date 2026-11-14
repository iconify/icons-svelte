<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="hoesb6b5v"/><path class="q1n8vnlkp"/><path class="iqeu88a9k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:mention-teammate" {...props}></Icon>
<style>
:global(.hoesb6b5v) {
  d: path("M5 2.5h14A2.5 2.5 0 0 1 21.5 5v10.5A2.5 2.5 0 0 1 19 18h-8l-4 3.5V18H5a2.5 2.5 0 0 1-2.5-2.5V5A2.5 2.5 0 0 1 5 2.5Z");
}

:global(.iqeu88a9k) {
  d: path("M14 8.25v3a1.5 1.5 0 0 0 3 0v-1a5 5 0 1 0-1.5 3.5");
}

:global(.q1n8vnlkp) {
  d: path("M10 10.25a2 2 0 1 0 4 0a2 2 0 1 0-4 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
