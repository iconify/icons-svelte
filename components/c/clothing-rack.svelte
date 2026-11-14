<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="hjiokve4n"/><path class="grygxjbqf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:clothing-rack" {...props}></Icon>
<style>
:global(.grygxjbqf) {
  d: path("M7.75 4.5v2l2.5 2.25v7.75h-5V8.75l2.5-2.25m8.5-2v2l2.25 2l.25 8.5h-5L14 8.5l2.25-2");
}

:global(.hjiokve4n) {
  d: path("M2.5 21.5v-17h19v17");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
