<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="xuooclz3l"/><path class="kojsju5nf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:coaching-session" {...props}></Icon>
<style>
:global(.kojsju5nf) {
  d: path("M7 13a2 2 0 1 0 4 0a2 2 0 1 0-4 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.xuooclz3l) {
  d: path("M9 6.5h11a1 1 0 0 1 1 1v2a1 1 0 0 1-1 1h-5a6.5 6.5 0 1 1-6-4Z");
}

</style>
