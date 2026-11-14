<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p9zbgccgf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:gemba-walk" {...props}></Icon>
<style>
:global(.p9zbgccgf) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 7.75a2.75 4 0 1 0 5.5 0a2.75 4 0 1 0-5.5 0Zm9 3.25a2.75 4 0 1 0 5.5 0a2.75 4 0 1 0-5.5 0Zm-8.5 4.25a2.25 1.75 0 1 0 4.5 0a2.25 1.75 0 1 0-4.5 0Zm9 3.25a2.25 1.75 0 1 0 4.5 0a2.25 1.75 0 1 0-4.5 0Z");
}

</style>
