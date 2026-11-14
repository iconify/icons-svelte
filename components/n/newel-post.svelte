<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="p51hyn75k"/><path class="id4i1xt9m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:newel-post" {...props}></Icon>
<style>
:global(.id4i1xt9m) {
  d: path("M7 9.5H3V21h7.25v-3.5h3.5V14h3.5v-3.5H21V21M7 9.5V21m0-8.5l14-7");
}

:global(.p51hyn75k) {
  d: path("M2.5 7a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
