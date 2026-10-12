<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="l1nb51yql"/><path class="j0ow62bhu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:chatbot-face-sharp" {...props}></Icon>
<style>
:global(.j0ow62bhu) {
  d: path("M7.75 9h2.5v3.5h-2.5zm6 0h2.5v3.5h-2.5z");
}

:global(.l1nb51yql) {
  d: path("M6 4.75h15.25v12.5h-8.5l-3.9 3.15l-.973.965L8 20v-2.75H2.75V4.75z");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
