<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="plrxxqqma"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:axa" {...props}></Icon>
<style>
:global(.plrxxqqma) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.5 6.765L28.139 25.54m-1.06 1.768L15.92 41.235m-10.42 0l10.695-13.927l4.073 13.927l10.673-13.927l4.073 13.927M20.196 27.308l4.8 13.927m-14.148-6.963h7.384m7.373 0h7.373");
}

</style>
