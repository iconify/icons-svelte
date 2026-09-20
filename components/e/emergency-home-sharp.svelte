<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yawaslb1j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:emergency-home-sharp" {...props}></Icon>
<style>
:global(.yawaslb1j) {
  fill: currentColor;
  d: path("M11.5 13.173h1v-5.23h-1zm.934 2.049q.182-.181.182-.433t-.182-.434t-.434-.182t-.434.182t-.182.433t.182.434t.434.182t.434-.182M12 21.377L2.623 12L12 2.623L21.377 12z");
}

</style>
