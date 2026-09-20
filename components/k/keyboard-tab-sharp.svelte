<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bgpe15btd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:keyboard-tab-sharp" {...props}></Icon>
<style>
:global(.bgpe15btd) {
  fill: currentColor;
  d: path("M20 17.5v-11h1v11zm-7.673-.212l-.713-.688l4.1-4.1H3v-1h12.694l-4.056-4.1l.689-.688L17.616 12z");
}

</style>
