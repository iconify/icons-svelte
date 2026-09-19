<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="orytrlb9j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:apowermirror" {...props}></Icon>
<style>
:global(.orytrlb9j) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m23.979 27.065l7.687-13.314L43.5 34.249H28.168L16.334 13.751L4.5 34.249h12.686");
}

</style>
