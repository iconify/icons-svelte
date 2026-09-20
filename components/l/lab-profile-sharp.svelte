<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mjo_wjbji"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:lab-profile-sharp" {...props}></Icon>
<style>
:global(.mjo_wjbji) {
  fill: currentColor;
  d: path("M8 12h8v-2H8zm0-4h8V6H8zm12 12.55L14.975 14H4V2h16zM4 22v-6h10l4.6 6z");
}

</style>
