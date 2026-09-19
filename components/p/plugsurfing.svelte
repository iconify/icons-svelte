<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="f0rv2qb9x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:plugsurfing" {...props}></Icon>
<style>
:global(.f0rv2qb9x) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.712 4.344L13.5 25.674l11.06-.262l-7.346 17.932L34.5 20.657l-11.883.294Z");
}

</style>
