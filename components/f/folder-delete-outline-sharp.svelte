<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d0dkaibqd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:folder-delete-outline-sharp" {...props}></Icon>
<style>
:global(.d0dkaibqd) {
  fill: currentColor;
  d: path("M2 20V4h8l2 2h10v14zm2-2h16V8h-8.825l-2-2H4zm0 0V6zm9-1h5v-5.5h1V10h-2.5V9h-2v1H12v1.5h1zm1.5-1.5v-4h2v4z");
}

</style>
