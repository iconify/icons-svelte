<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="gro7n3nox"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:installerx" {...props}></Icon>
<style>
:global(.gro7n3nox) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M7.435 38.784H23.64l-6.974-7.581zm19.361-.551L5.5 15.043h19.055l10.43 11.57zm.395-24.574l9.468 10.614V9.216h-6.446zm12.003-2.935v4.154H42.5z");
}

</style>
