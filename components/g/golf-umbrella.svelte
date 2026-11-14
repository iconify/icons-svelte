<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h01un54oo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:golf-umbrella" {...props}></Icon>
<style>
:global(.h01un54oo) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 12a9.5 9.5 0 0 1 19 0a2.5 2.5 0 0 0-4.75 0A2.5 2.5 0 0 0 12 12a2.5 2.5 0 0 0-4.75 0a2.5 2.5 0 0 0-4.75 0Zm9.5 0v7a1.75 1.75 0 0 1-3.5 0");
}

</style>
