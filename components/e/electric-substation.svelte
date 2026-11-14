<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="njyew0pvf"/><path class="ftuhgq31z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:electric-substation" {...props}></Icon>
<style>
:global(.ftuhgq31z) {
  d: path("M9.75 11.25L7 15h3l-2.75 3.75");
}

:global(.njyew0pvf) {
  d: path("M3.5 8.5h10v13h-10Zm14.5 13V4m-2.5 1.5h5m-18 16h19");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
