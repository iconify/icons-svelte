<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kt5ihqseo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:rockfall" {...props}></Icon>
<style>
:global(.kt5ihqseo) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m2.5 5.5l16.5 15h2.5m-9-13l.5-3l4-1L18.5 7L15 8.5ZM18 11l3-.5l.5 3.5l-3 1Z");
}

</style>
