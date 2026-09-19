<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="akbn5joor"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:catawiki" {...props}></Icon>
<style>
:global(.akbn5joor) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.677 42.5c-21.333-4.206-21.333-32.664 0-37h12.617l.03 37z");
}

</style>
