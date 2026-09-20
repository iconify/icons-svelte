<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t0j19b4km"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:android-cell-4-bar-sharp" {...props}></Icon>
<style>
:global(.t0j19b4km) {
  fill: currentColor;
  d: path("M1.5 20v-8h3v8zm6 0V9.5h3V20zm6 0V7h3v13zm6 0V4h3v16z");
}

</style>
