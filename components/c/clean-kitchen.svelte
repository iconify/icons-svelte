<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zfa80zbvu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:clean-kitchen" {...props}></Icon>
<style>
:global(.zfa80zbvu) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 11.5h14V16a4 4 0 0 1-4 4H8a4 4 0 0 1-4-4ZM2.5 13H4m1-4.5h12m-6-2v2m7.75-5.75l.884 1.366L21 5l-1.366.884l-.884 1.366l-.884-1.366L16.5 5l1.366-.884Z");
}

</style>
