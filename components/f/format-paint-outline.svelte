<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d7angqbta"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:format-paint-outline" {...props}></Icon>
<style>
:global(.d7angqbta) {
  fill: currentColor;
  d: path("M11 22q-.825 0-1.412-.587T9 20v-4H6q-.825 0-1.412-.587T4 14V7q0-1.65 1.175-2.825T8 3h12v11q0 .825-.587 1.413T18 16h-3v4q0 .825-.587 1.413T13 22zM6 10h12V5h-1v4h-2V5h-1v2h-2V5H8q-.825 0-1.412.588T6 7zm0 4h12v-2H6zm0 0v-2z");
}

</style>
