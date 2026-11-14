<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bdlfycban"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:clothes-peg" {...props}></Icon>
<style>
:global(.bdlfycban) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 3za3 3 0 0 1 3 3v12.5a3 3 0 0 1-3 3a3 3 0 0 1-3-3V6a3 3 0 0 1 3-3M2.5 7H9m6 0h6.5M12 3v6.5M9 13h6");
}

</style>
