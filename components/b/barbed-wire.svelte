<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gd-_eccbw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:barbed-wire" {...props}></Icon>
<style>
:global(.gd-_eccbw) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 9h19m-19 6h19m-15-7.5l3 3m0-3l-3 3m8-3l3 3m0-3l-3 3m-4 3l3 3m0-3l-3 3");
}

</style>
