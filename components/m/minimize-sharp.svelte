<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nid-gh7jy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:minimize-sharp" {...props}></Icon>
<style>
:global(.nid-gh7jy) {
  fill: currentColor;
  d: path("M6 21v-2h12v2z");
}

</style>
