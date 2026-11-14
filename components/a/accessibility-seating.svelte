<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q0i4xsbta"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:accessibility-seating" {...props}></Icon>
<style>
:global(.q0i4xsbta) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m4.5 2.5l1 10H14m-8.5 0l-1.5 9m9-9l.21 1.888M17.5 13h.01m-.01 2.75V18h2.75l1 2.75m-2.618-.375a2.75 2.75 0 1 1-3.757-3.757");
}

</style>
