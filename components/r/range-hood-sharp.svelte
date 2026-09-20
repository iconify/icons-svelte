<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cuhbyg6-n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:range-hood-sharp" {...props}></Icon>
<style>
:global(.cuhbyg6-n) {
  fill: currentColor;
  d: path("M3.55 12.885L8 8.423V4h8v4.423l4.462 4.462zM3 19v-5.115h18V19zm7-2.608h4v-.884h-4z");
}

</style>
