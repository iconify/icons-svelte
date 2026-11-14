<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yg3pdvrta"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:good-lift" {...props}></Icon>
<style>
:global(.yg3pdvrta) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 8h19m-17-5h2.75v10H4.5Zm12.25 0h2.75v10h-2.75Zm-2 15l2 2L21 15.75");
}

</style>
