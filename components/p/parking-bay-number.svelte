<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="hjw8ws4ni"/><path class="n391k4b8t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:parking-bay-number" {...props}></Icon>
<style>
:global(.hjw8ws4ni) {
  d: path("M3 21L7.5 3.5h9L21 21");
}

:global(.n391k4b8t) {
  d: path("m10.5 10.5l2-1.75V17m-2 0h4");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
