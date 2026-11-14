<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="zkxfm7bmr"/><path class="us6w3gb9h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:dashboard-lock" {...props}></Icon>
<style>
:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.us6w3gb9h) {
  d: path("m6 8l3-2.25l3.5 1.5L18 5.5m-3.5 12h7V22h-7Zm1.75 0v-1.25a1.75 1.75 0 0 1 3.5 0v1.25");
}

:global(.zkxfm7bmr) {
  d: path("M11.7 21.5H2.5v-19h19v10.9M2.5 11h19M11 11v10.5");
}

</style>
