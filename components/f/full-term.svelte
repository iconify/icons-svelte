<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="srqwc63fu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:full-term" {...props}></Icon>
<style>
:global(.srqwc63fu) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.5 33.754c-5.361 4.24-12.13 6.77-19.5 6.77s-14.139-2.53-19.5-6.77L17.175 7.477c2.064 1 4.377 1.56 6.825 1.56s4.76-.56 6.825-1.56z");
}

</style>
