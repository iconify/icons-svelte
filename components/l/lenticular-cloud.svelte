<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t-uo10bby"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:lenticular-cloud" {...props}></Icon>
<style>
:global(.t-uo10bby) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 8q9-6.5 18 0q-9 3.5-18 0Zm-.5 12L9 13.5l3.5 3.5l3-3l6 6");
}

</style>
