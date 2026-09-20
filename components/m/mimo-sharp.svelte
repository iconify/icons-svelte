<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w1iybfyae"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:mimo-sharp" {...props}></Icon>
<style>
:global(.w1iybfyae) {
  fill: currentColor;
  d: path("M7.192 20v-1.538l.77-.77H3V4h18v13.692h-4.962l.77.77V20z");
}

</style>
