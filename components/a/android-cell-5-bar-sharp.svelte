<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n0gygqnek"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:android-cell-5-bar-sharp" {...props}></Icon>
<style>
:global(.n0gygqnek) {
  fill: currentColor;
  d: path("M1 20v-6h3v6zm4.75 0v-8h3v8zm4.75 0V9h3v11zm4.75 0V7h3v13zM20 20V4h3v16z");
}

</style>
