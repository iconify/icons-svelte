<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="sykfadwpy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:lanxchange" {...props}></Icon>
<style>
:global(.sykfadwpy) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 24L5.5 5.5s8.75 17.633 9.25 18.5c-.5.868-9.25 18.5-9.25 18.5zl18.5 18.5S33.75 24.868 33.25 24c.499-.864 9.25-18.5 9.25-18.5Z");
}

</style>
