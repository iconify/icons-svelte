<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ebp7y0bnn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:learn-javascript" {...props}></Icon>
<style>
:global(.ebp7y0bnn) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.599 6.421V41.58L5.5 37.885m37-31.075H27.368v18.915l12.553-1.633l-1.032 14.014l-12.99 3.473");
}

</style>
