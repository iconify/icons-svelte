<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o84x0bcad"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:museum-sharp" {...props}></Icon>
<style>
:global(.o84x0bcad) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m4.1 7.97l7.05-4.44L12 3l.85.53l7.05 4.44l.85.53H3.25zm2.4 3.53V18m3.75-6.5V18m3.5-6.5V18m3.75-6.5V18M3.25 20.75h17.5");
}

</style>
