<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="q0f-lgkcm"/><path class="quenbx46y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:amber-alert" {...props}></Icon>
<style>
:global(.q0f-lgkcm) {
  d: path("M5 2.5h14v19H5Z");
}

:global(.quenbx46y) {
  d: path("M7.75 14h8.5L15 12.5v-3a3 3 0 0 0-6 0v3Zm3 3h2.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
