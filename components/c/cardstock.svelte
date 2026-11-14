<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="lowe75bmn"/><path class="qory6h5iq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:cardstock" {...props}></Icon>
<style>
:global(.lowe75bmn) {
  d: path("M4 2.5h9.5l5 5v11H4Z");
}

:global(.qory6h5iq) {
  d: path("M4 18.5L6.5 21H21V10l-2.5-2.5m-5-5v5h5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
