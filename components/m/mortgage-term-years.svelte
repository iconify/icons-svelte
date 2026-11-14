<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="odaz_5sfe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:mortgage-term-years" {...props}></Icon>
<style>
:global(.odaz_5sfe) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m14 11l3.75-4l3.75 4v7.5H14ZM2.5 14.75H12m-1.5-1.5l1.5 1.5l-1.5 1.5M2.75 13.5V16m2.75-2.5V16m2.75-2.5V16");
}

</style>
