<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="irli1ibut"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:hair-clip-sharp" {...props}></Icon>
<style>
:global(.irli1ibut) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 4.5h14.5V9H4.75zM6.5 9.75v7.583L9 19m1.5-9.25v8m3-8v8m4-8v7.583L15 19");
}

</style>
