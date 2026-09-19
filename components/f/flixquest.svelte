<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="byqy7ccma"/><path class="xlpg5ldua"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:flixquest" {...props}></Icon>
<style>
:global(.byqy7ccma) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.24 28.067v-10.83L30.707 4.5l9.053 5.338z");
}

:global(.xlpg5ldua) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m8.24 28.067l18.02-10.422l8.956 5.304L8.24 38.432zm0 10.365l9.132-5.229V43.5z");
}

</style>
