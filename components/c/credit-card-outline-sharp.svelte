<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zp7_wulai"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:credit-card-outline-sharp" {...props}></Icon>
<style>
:global(.zp7_wulai) {
  fill: currentColor;
  d: path("M3 19V5h18v14zM4 8.808h16V6H4zM4 18h16v-6.808H4zm0 0V6z");
}

</style>
