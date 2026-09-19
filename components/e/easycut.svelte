<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="cgc4jiiot"/><path class="lqily1bza"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:easycut" {...props}></Icon>
<style>
:global(.cgc4jiiot) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m41.818 5.5l-35.635 37v-37l35.614 37");
}

:global(.lqily1bza) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m34.932 24.118l6.798-6.798v13.51z");
}

</style>
