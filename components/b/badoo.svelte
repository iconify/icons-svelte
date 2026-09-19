<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="p6h93ybcj"/><path class="gpg4b3b0v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:badoo" {...props}></Icon>
<style>
:global(.gpg4b3b0v) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.568 21.338a8.432 8.432 0 0 0 16.864 0");
}

:global(.p6h93ybcj) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.053 9.867a10.014 10.014 0 0 1 8.447 9.89a19.5 19.5 0 0 1-39 0A9.993 9.993 0 0 1 24 16.663a9.95 9.95 0 0 1 11.053-6.796");
}

</style>
