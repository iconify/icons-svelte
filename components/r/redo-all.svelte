<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ca5wyj4hh"/><path class="f9m7n91js"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:redo-all" {...props}></Icon>
<style>
:global(.ca5wyj4hh) {
  d: path("M16.5 9.5H9a5 5 0 0 0 0 10h4");
}

:global(.f9m7n91js) {
  d: path("m12.5 5.5l4 4l-4 4m4-8l4 4l-4 4");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
