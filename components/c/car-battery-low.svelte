<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r7hg2jwkz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:car-battery-low" {...props}></Icon>
<style>
:global(.r7hg2jwkz) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M15.2 18.5H2.5v-13h17v6.2m-14-6.2v-2h3v2m5 0v-2h3v2M6 15.5h4.5m7.5-1V18m0 3h.01");
}

</style>
