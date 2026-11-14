<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lhqpeom4k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:pickleball-paddle" {...props}></Icon>
<style>
:global(.lhqpeom4k) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 2.5h11a2 2 0 0 1 2 2V13a2 2 0 0 1-2 2h-11a2 2 0 0 1-2-2V4.5a2 2 0 0 1 2-2ZM10 15h4v6.5h-4Zm-.5-8.5h.01m4.99 0h.01M9.5 11h.01m4.99 0h.01");
}

</style>
