<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m73b-cbfo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:magnify-fullscreen-sharp" {...props}></Icon>
<style>
:global(.m73b-cbfo) {
  fill: currentColor;
  d: path("M3 19V5h18v14zm11.5-5.308h1V11.5h2.192v-1H15.5V8.308h-1V10.5h-2.192v1H14.5z");
}

</style>
