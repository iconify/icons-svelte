<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ekwha6z8b"/><path class="uph4zqc9i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:calendar-google-7" {...props}></Icon>
<style>
:global(.ekwha6z8b) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m22.144 28.5l4.837-9h-5.962");
}

:global(.uph4zqc9i) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h24l9-9v-24a4 4 0 0 0-4-4m-5 0v37m-19-28v28m28-9h-37m37-19h-28");
}

</style>
