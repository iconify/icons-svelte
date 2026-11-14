<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="t40azhbpj"/><path class="qzxgnzbmc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:basketball-dunk" {...props}></Icon>
<style>
:global(.qzxgnzbmc) {
  d: path("M16 9.5h5m-4.5 0l.75 4h2.5l.75-4");
}

:global(.t40azhbpj) {
  d: path("M3.75 8.5a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0ZM8 12.75l8.25-5.5M8 12.75L9 17m-3.5 4L9 17l3.5 3.5m3.75-13.25a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
