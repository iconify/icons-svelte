<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b2w4nqbdw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:louvred-roof-pergola" {...props}></Icon>
<style>
:global(.b2w4nqbdw) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 9.5h19M5 9.5V21M19 9.5V21M4.5 6.5l3-3.5m3 3.5l3-3.5m3 3.5l3-3.5");
}

</style>
