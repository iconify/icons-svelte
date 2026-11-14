<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jolfyzezz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:erlenmeyer-flask" {...props}></Icon>
<style>
:global(.jolfyzezz) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 3v5.75l-5 9.75C3.9 19.75 4.6 21 6 21h12c1.4 0 2.1-1.25 1.5-2.5l-5-9.75V3M8 3h8M7 15h10");
}

</style>
