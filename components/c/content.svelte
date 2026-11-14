<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="xcir0ybyg"/><path class="vwpu23b9b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:content" {...props}></Icon>
<style>
:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.vwpu23b9b) {
  d: path("M2.5 17L8 11.5l4.187 4.187M13.5 8.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm1.5 6.25l6.25 3.5l-6.25 3.5Z");
}

:global(.xcir0ybyg) {
  d: path("M12.2 20.5H2.5v-17h19v11.7");
}

</style>
