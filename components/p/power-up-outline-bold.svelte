<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eqnkueqyn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:power-up-outline-bold" {...props}></Icon>
<style>
:global(.eqnkueqyn) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
  d: path("m16 3 -8 8h5l-9 9");
}

</style>
