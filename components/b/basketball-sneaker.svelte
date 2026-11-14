<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uvxbu5bti"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:basketball-sneaker" {...props}></Icon>
<style>
:global(.uvxbu5bti) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 3h6.5l.5 6.5l7.5 4a3 3 0 0 1 2.5 3V20H3ZM3 17h18M3 7h7.75");
}

</style>
