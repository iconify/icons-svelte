<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qucdmlbcc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:phone-android-sharp" {...props}></Icon>
<style>
:global(.qucdmlbcc) {
  fill: currentColor;
  d: path("M10 20h4v-1h-4zm-5 3V1h14v22zm2-7h10V6H7z");
}

</style>
