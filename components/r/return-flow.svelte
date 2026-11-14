<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="thwb36w5b"/><path class="exi9h5u6a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:return-flow" {...props}></Icon>
<style>
:global(.exi9h5u6a) {
  d: path("m8.5 14l-3 3l3 3M8 4l2.5 2.5L8 9");
}

:global(.thwb36w5b) {
  d: path("M2.5 6.5H15A5.25 5.25 0 0 1 15 17H5.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
