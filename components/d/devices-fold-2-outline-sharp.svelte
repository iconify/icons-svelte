<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cl2e2gb9s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:devices-fold-2-outline-sharp" {...props}></Icon>
<style>
:global(.cl2e2gb9s) {
  fill: currentColor;
  d: path("M5 21V3h13.95l4 10H19v8zm4.4-10H20l-2.4-6H7zM7 19h10v-6H8.05L7 10.375zm6.5-11");
}

</style>
