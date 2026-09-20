<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hut2hdf3b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:playlist-remove-sharp" {...props}></Icon>
<style>
:global(.hut2hdf3b) {
  fill: currentColor;
  d: path("m14.496 21.308l-.708-.708l2.6-2.6l-2.6-2.6l.708-.708l2.6 2.6l2.6-2.6l.708.708l-2.6 2.6l2.6 2.6l-.708.708l-2.6-2.6zM3.596 15.5v-1h7v1zm0-4v-1h11v1zm0-4v-1h11v1z");
}

</style>
