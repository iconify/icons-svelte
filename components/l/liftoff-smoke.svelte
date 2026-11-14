<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="urqxyb15f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:liftoff-smoke" {...props}></Icon>
<style>
:global(.urqxyb15f) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 17A3.5 3.5 0 0 1 8 11a4.5 4.5 0 0 1 8-.5a3.5 3.5 0 0 1 3.5 6.5m-17 0h19");
}

</style>
