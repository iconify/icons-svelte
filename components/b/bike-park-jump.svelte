<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bko4__5dx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:bike-park-jump" {...props}></Icon>
<style>
:global(.bko4__5dx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 20.5c6.5 0 10-2 12-7v7m-12 0h19M13.5 7a4 4 0 1 0 8 0a4 4 0 1 0-8 0Zm4 0h.01");
}

</style>
