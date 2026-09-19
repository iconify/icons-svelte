<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="wduo3tydo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:kion" {...props}></Icon>
<style>
:global(.wduo3tydo) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.167 20h14v8h-14zM43.5 20v8l-8-8v8m-20.667-8v8M4.5 20v8m7-8L8 24l3.5 4M8 24H4.5");
}

</style>
