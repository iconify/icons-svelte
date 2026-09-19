<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="unug2mbnm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:arbetsfor" {...props}></Icon>
<style>
:global(.unug2mbnm) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.71 3.71C40.77 4.35 50.61 28 40.6 44.26M17.4 16.51A13.88 13.88 0 1 1 7.59 40.2a13.89 13.89 0 0 1 9.81-23.69");
}

</style>
