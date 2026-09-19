<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="fmemu4bok"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:delta-dental" {...props}></Icon>
<style>
:global(.fmemu4bok) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 15.989h-9.25L5.5 32.01l4.625 8.01h27.75l4.625-8.01L28.625 7.978h-9.25L33.25 32.011h-18.5z");
}

</style>
