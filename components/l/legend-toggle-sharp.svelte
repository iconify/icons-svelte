<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lptio0b6d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:legend-toggle-sharp" {...props}></Icon>
<style>
:global(.lptio0b6d) {
  fill: currentColor;
  d: path("M4.5 18.27v-1h15v1zm0-3.77v-1h15v1zm0-4.154V9.17l5.48-3.342L15 9.397l4.5-3.205v1.239L15 10.616L9.944 7.035z");
}

</style>
