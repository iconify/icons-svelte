<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fa9znlbzp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:appliance-manual" {...props}></Icon>
<style>
:global(.fa9znlbzp) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 6.5Q8 4 2.5 4.5v14q5.5-.5 9.5 2q4-2.5 9.5-2v-14Q16 4 12 6.5Zm0 0v14");
}

</style>
