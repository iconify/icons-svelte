<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t87kkqbee"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:backdrop-roll-sharp" {...props}></Icon>
<style>
:global(.t87kkqbee) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 2.75h18.5v3.5H2.75zm3.5 3.5h11.5V19H6.25v-2.5Zm-2.5 0v15m16.5-15v15");
}

</style>
