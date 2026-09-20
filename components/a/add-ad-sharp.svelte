<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q-8_jfm5y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:add-ad-sharp" {...props}></Icon>
<style>
:global(.q-8_jfm5y) {
  fill: currentColor;
  d: path("M18 20v-3h-3v-2h3v-3h2v3h3v2h-3v3zM1 21V3h18v7h-2V8H3v11h13v2z");
}

</style>
