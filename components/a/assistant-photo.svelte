<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gvedy3bot"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:assistant-photo" {...props}></Icon>
<style>
:global(.gvedy3bot) {
  fill: currentColor;
  d: path("M14.4 6L14 4H5v17h2v-7h5.6l.4 2h7V6z");
}

</style>
