<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="i8vvkrble"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:fluffy-fall-alt" {...props}></Icon>
<style>
:global(.i8vvkrble) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.741 22.84c.477 2.209 1.685 2.962 3.259 2.962s2.782-.753 3.259-2.962m6.783-.642H44.5m-41 0h10.458");
}

</style>
