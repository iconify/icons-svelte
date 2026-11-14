<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uso4ihbsw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:railway-line" {...props}></Icon>
<style>
:global(.uso4ihbsw) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m4.5 21.5l4-19m11 19l-4-19M3.75 18h16.5M5 12h14M6.5 6h11");
}

</style>
