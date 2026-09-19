<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="pivkfrblr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:delta-touch" {...props}></Icon>
<style>
:global(.pivkfrblr) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.595 43.5V12.441H10.6L8.482 4.5h31.036l-2.137 8.014h-8.418V35.03z");
}

</style>
