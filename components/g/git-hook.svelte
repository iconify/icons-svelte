<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="hex9h-3ie"/><path class="umncu1g5k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:git-hook" {...props}></Icon>
<style>
:global(.hex9h-3ie) {
  d: path("M14.5 4.25a2 2 0 1 0 4 0a2 2 0 1 0-4 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.umncu1g5k) {
  d: path("M16.5 6.25V14a5.5 5.5 0 0 1-11 0v-4m0 0l3 3");
}

</style>
