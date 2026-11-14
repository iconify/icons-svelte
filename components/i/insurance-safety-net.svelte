<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gf0xjbclo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:insurance-safety-net" {...props}></Icon>
<style>
:global(.gf0xjbclo) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 4v16M21 4v16M3 6c3.5 11.5 14.5 11.5 18 0M3 6h18M8 6l.5 6.75M12 6v8.5M16 6l-.5 6.75");
}

</style>
