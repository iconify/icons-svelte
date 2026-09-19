<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="i9clfwm2k"/><path class="agig0lbno"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:photo-widget" {...props}></Icon>
<style>
:global(.agig0lbno) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12 30.742V17.264h4.38c2.528 0 4.55 2.021 4.55 4.549s-2.022 4.549-4.55 4.549H12m24-9.104l-3.37 13.478l-3.369-13.478l-3.369 13.478l-3.37-13.478");
}

:global(.i9clfwm2k) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

</style>
