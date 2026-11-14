<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="cgbkqfb5l"/><path class="ojxamrbwd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:arrow-turn-down-right" {...props}></Icon>
<style>
:global(.cgbkqfb5l) {
  d: path("M3.5 5h8a5 5 0 0 1 5 5v9");
}

:global(.ojxamrbwd) {
  d: path("m12.5 15l4 4l4-4");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
