<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="fzwvrvbkj"/><path class="pep052bmd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:backstage-pass" {...props}></Icon>
<style>
:global(.fzwvrvbkj) {
  d: path("M6.5 9h11v12.5h-11Zm2 0l2.75-5.5q.75-1.5 1.5 0L15.5 9");
}

:global(.pep052bmd) {
  d: path("M10 13.75a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm-.5 4.75h5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
