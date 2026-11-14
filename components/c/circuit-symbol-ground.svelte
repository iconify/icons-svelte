<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="io2k2gbyh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:circuit-symbol-ground" {...props}></Icon>
<style>
:global(.io2k2gbyh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 3v9m-7 0h14M7.5 15.5h9M10 19h4");
}

</style>
