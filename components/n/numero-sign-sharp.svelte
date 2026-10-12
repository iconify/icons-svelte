<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pnt6oifjy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:numero-sign-sharp" {...props}></Icon>
<style>
:global(.pnt6oifjy) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 19.5v-15l9.5 15v-15m4.75 2a2.25 2.25 0 1 1 0 4.5a2.25 2.25 0 1 1 0-4.5m-2.25 8h4.5");
}

</style>
