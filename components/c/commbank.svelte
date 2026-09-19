<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="fhn-lv1-v"/><path class="s7fpvo7ii"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:commbank" {...props}></Icon>
<style>
:global(.fhn-lv1-v) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24.363 3.863l20.5 20.5l-20.5 20.499l-20.5-20.5z");
}

:global(.s7fpvo7ii) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m39.53 19.03l-7.417 7.416l-7.75 18.417");
}

</style>
