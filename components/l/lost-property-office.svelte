<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="bqcr0kphh"/><path class="ls2yoovyv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:lost-property-office" {...props}></Icon>
<style>
:global(.bqcr0kphh) {
  d: path("M4.5 9h15v12.25h-15Zm0 0l-2-5.5h7L12 9m7.5 0l2-5.5h-7L12 9");
}

:global(.ls2yoovyv) {
  d: path("M10 13.75a2 2 0 1 1 2 2v.75m0 2.25h.01");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
