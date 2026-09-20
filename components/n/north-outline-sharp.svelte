<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q-1b2fjdo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:north-outline-sharp" {...props}></Icon>
<style>
:global(.q-1b2fjdo) {
  fill: currentColor;
  d: path("M11.5 21V4.864l-5.158 5.152l-.688-.689L12 2.981l6.346 6.346l-.688.714L12.5 4.883V21z");
}

</style>
