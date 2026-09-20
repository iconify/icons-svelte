<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m0k5q8nkc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:position-bottom-left-sharp" {...props}></Icon>
<style>
:global(.m0k5q8nkc) {
  fill: currentColor;
  d: path("M6.616 16.808h8v-2h-8zM4 20V4h16v16z");
}

</style>
