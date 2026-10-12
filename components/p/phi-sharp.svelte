<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cvfbhjbfe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:phi-sharp" {...props}></Icon>
<style>
:global(.cvfbhjbfe) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 6.75c4 0 6.75 2.25 6.75 5.25S16 17.25 12 17.25S5.25 15 5.25 12S8 6.75 12 6.75Zm0-4v18.5");
}

</style>
