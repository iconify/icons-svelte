<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ssdnkevch"/><path class="btj9ltr1g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:kyivdigital" {...props}></Icon>
<style>
:global(.btj9ltr1g) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m31 28.92l-12.724-9L31 10.98m-12.724 8.94H17");
}

:global(.ssdnkevch) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M41.013 33.553L24.027 43.5l-17.04-9.947V4.5h34.026zM17 10.92v18");
}

</style>
