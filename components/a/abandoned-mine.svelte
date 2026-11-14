<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ov4dr0bxa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:abandoned-mine" {...props}></Icon>
<style>
:global(.ov4dr0bxa) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m7 3.5l-2.5 18M17 3.5l2.5 18m-16-18h17m-18 18h19m-17-12l15 3M4 17.5L20 15");
}

</style>
