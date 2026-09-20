<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tid-pwb3b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:home-sharp" {...props}></Icon>
<style>
:global(.tid-pwb3b) {
  fill: currentColor;
  d: path("M5 20V9.5l7-5.288L19 9.5V20h-5.192v-6.384h-3.616V20z");
}

</style>
