<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z1_g42tus"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:edit-note-outline-sharp" {...props}></Icon>
<style>
:global(.z1_g42tus) {
  fill: currentColor;
  d: path("M4 14v-2h7v2zm0-4V8h11v2zm0-4V4h11v2zm9 14v-3.075l6.575-6.55l3.075 3.05L16.075 20zm7.5-6.575l-.925-.925zm-6 5.075h.95l3.025-3.05l-.45-.475l-.475-.45l-3.05 3.025zm3.525-3.525l-.475-.45l.925.925z");
}

</style>
