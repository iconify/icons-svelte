<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="vcq7wer-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:orange-money" {...props}></Icon>
<style>
:global(.vcq7wer-a) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M6.5 15.402H22v15.5m0-15.5l-17.5 17.5m37-.304H26v-15.5m0 15.5l17.5-17.5");
}

</style>
