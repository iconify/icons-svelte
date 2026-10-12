<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="vf_31rbpy"/><path class="h4kmvibqu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:chart-annotation-sharp" {...props}></Icon>
<style>
:global(.h4kmvibqu) {
  d: path("m7 17.25l3.75-4L14 15.5l6.25-5.25m-9.75-7.5h9.75V8h-4.5l-.65.76l-.2.23l-.65.76l-.65-.76l-.2-.23l-.65-.76H9.5V2.75zm1.75 2.75h5.25");
}

:global(.vf_31rbpy) {
  d: path("M3.75 3.75v16.5h16.5");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
