<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="cap0h-bmd"/><path class="geu0lxbhh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:halyk" {...props}></Icon>
<style>
:global(.cap0h-bmd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.308 20.793V42.5m23.384-21.707V42.5M12.308 31.606h23.384m5.119-13.15L24 5.5L7.189 18.456");
}

:global(.geu0lxbhh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37.434 15.859V8.301h-5.553v3.272");
}

</style>
