<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="o5m802bqa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:ripple" {...props}></Icon>
<style>
:global(.o5m802bqa) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 43.5A14.27 14.27 0 0 1 9.75 29.32C9.75 19.89 24 4.5 24 4.5s14.25 15.39 14.25 24.82A14.27 14.27 0 0 1 24 43.5");
}

</style>
